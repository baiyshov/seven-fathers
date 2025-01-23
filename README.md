
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Санжыра</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <h1>Санжыра</h1>
    <div id="tree" class="tree">
        </div>
    </div>
    
    <script src="./script.js"></script>
</body>
</html>


const sanjyraData = {
    name: "Долон бий",
    children: [
        {
            name: "Ак уул",
            children: [
                {
                    name: "Тагай",
                    children: [
                        {
                            name: "Саяк",
                            children: [
                                {
                                    name: "Муратай",
                                    children: [
                                        {
                                            name: "Жусупбек",
                                            children: [
                                                {
                                                    name: "Абдрайым",
                                                    children: [
                                                        {
                                                            name: "Байызбек",
                                                            children: [
                                                                {
                                                                    name: "Садык",
                                                                    children: [
                                                                        {
                                                                            name: "Каба",
                                                                            children: [
                                                                                {
                                                                                    name: "Шыкмамат",
                                                                                    children: [
                                                                                        {
                                                                                            name: "Кудаш",
                                                                                            children: [
                                                                                                {
                                                                                                    name: "Кудаяр",
                                                                                                    children: [
                                                                                                        {
                                                                                                            name: "Куткамерген",
                                                                                                            children: [ 
                                                                                                                {name: "Торпок"},
                                                                                                                {name: "Акылбек"},
                                                                                                                {name: "Кабатай"},
                                                                                                                {name: "Толок"},
                                                                                                                
                                                                                                                {
                                                                                                                    name: "Дуулат",
                                                                                                                    children: [
                                                                                                                        {name: "Боготой"},
                                                                                                                        {
                                                                                                                            name: "Барак",
                                                                                                                            children: [
                                                                                                                                {name:"Чекебай"},
                                                                                                                                {neme:"Туул"},
                                                                                                                                {
                                                                                                                                    name: "Байсейит",
                                                                                                                                    children: [
                                                                                                                                        {name:"Борук"},
                                                                                                                                        {
                                                                                                                                            name: "Жээнбай",
                                                                                                                                            children: [
                                                                                                                                                {name:"Адый"},
                                                                                                                                                {
                                                                                                                                                    name: "Кеңеш",
                                                                                                                                                    children: [
                                                                                                                                                        {
                                                                                                                                                            name: "Айтбай",
                                                                                                                                                            children: [
                                                                                                                                                                {
                                                                                                                                                                    name: "Мүсүралы",
                                                                                                                                                                    children: [
                                                                                                                                                                    {name:"Өзүбек",
                                                                                                                                                                    children:[
                                                                                                                                                                        {name:"Кедей",
                                                                                                                                                                        children:[
                                                                                                                                                                        {name:"Сейде"},
                                                                                                                                                                        {name:"Мелис"},
                                                                                                                                                                        {name:"Жакыпбек"},
                                                                                                                                                                        {name:"Каныбек"},
                                                                                                                                                                        {name:"Алыбек"}
                                                                                                                                                                        ]
                                                                                                                                                                        },
                                                                                                                                                                        {name:"Обоз",
                                                                                                                                                                        children:[
                                                                                                                                                                        {name:"Асылбек"},
                                                                                                                                                                        {name:"Аманбек"},
                                                                                                                                                                        {name:"Анарбек"},
                                                                                                                                                                        {name:"Женешкул"},
                                                                                                                                                                        ]
                                                                                                                                                                        },
                                                                                                                                                                        

                                                                                                                                                                    ]
                                                                                                                                                                    },
                                                                                                                                                                    {name:"Абды",
                                                                                                                                                                    children:[
                                                                                                                                                                    {name:"Адилет"},
                                                                                                                                                                    {name:"Канат"},
                                                                                                                                                                    {name:"Көкүл"},
                                                                                                                                                                    {name:"Адылбек"},
                                                                                                                                                                    ]
                                                                                                                                                                    },
                                                                                                                                                                        {
                                                                                                                                                                            name: "Абдыкалык",
                                                                                                                                                                            children: [
                                                                                                                                                                                {name:"Барыктабас"},
                                                                                                                                                                                {name:"Гулай"},
                                                                                                                                                                                {name:"Шайкул"},
                                                                                                                                                                                {name:"Кулушай"},
                                                                                                                                                                                {name: "Байыш",
                                                                                                                                                                                children:[
                                                                                                                                                                                {name:"Алмаз",
                                                                                                                                                                                children:[
                                                                                                                                                                                    {name:"Адеми"},
                                                                                                                                                                                    {name:"Кутман"},
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Гулкайыр",
                                                                                                                                                                                children:[
                                                                                                                                                                                    {name:"Айгул"},
                                                                                                                                                                                    {name:"Айсулуу"},
                                                                                                                                                                                    {name:"Умутай"},
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Гулбарчын",
                                                                                                                                                                                children:[
                                                                                                                                                                                    {name:"Эмир"},
                                                                                                                                                                                    {name:"Асел"}
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Кыяз",
                                                                                                                                                                                children:[
                                                                                                                                                                                    {name:"Иса"},
                                                                                                                                                                                    {name:"Изати"},
                                                                                                                                                                                    {name:"Алишер"},
                                                                                                                                                                                    {name:"Аянур"}
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Илияс",
                                                                                                                                                                                children:[
                                                                                                                                                                                    {name:"Баяман"},
                                                                                                                                                                                    {name:"Айтбай"},
                                                                                                                                                                                    {name:"Алим"},
                                                                                                                                                                                    {name:"Байзур"}
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Гулназ",
                                                                                                                                                                                children:[
                                                                                                                                                                                {name:"Улан"},
                                                                                                                                                                                {name:"Жаркынай"},
                                                                                                                                                                                {name:"Айжаркын"},
                                                                                                                                                                                {name:"Даян"}
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Илич",
                                                                                                                                                                                children:[
                                                                                                                                                                                    {name:"Илгиз"},
                                                                                                                                                                                    {name:"Эльвир"},
                                                                                                                                                                                    {name:"Бектур"}
                                                                                                                                                                                ]
                                                                                                                                                                                },
                                                                                                                                                                                {name:"Нияз"},
                                                                                                                                                                                ]
                                                                                                                                                                                }
                                                                                                                                                                            ]
                                                                                                                                                                        }
                                                                                                                                                                    ]
                                                                                                                                                                }
                                                                                                                                                            ]
                                                                                                                                                        }
                                                                                                                                                    ]
                                                                                                                                                }
                                                                                                                                            ]
                                                                                                                                        }
                                                                                                                                    ]
                                                                                                                                }
                                                                                                                            ]
                                                                                                                        }
                                                                                                                    ]
                                                                                                                }
                                                                                                            ]
                                                                                                        }
                                                                                                    ]
                                                                                                }
                                                                                            ]
                                                                                        }
                                                                                    ]
                                                                                }
                                                                            ]
                                                                        }
                                                                    ]
                                                                }
                                                            ]
                                                        }
                                                    ]
                                                }
                                            ]
                                        }
                                    ]
                                }
                            ]
                        }
                    ]
                }
            ]
        }
    ]
}


function createTreeNode(person) {
const personDiv = document.createElement('div');
personDiv.className = 'person';
personDiv.innerHTML = `<span>${person.name}</span>`;

if (person.children) {
const childrenContainer = document.createElement('div');
childrenContainer.className = 'children';
person.children.forEach(child => {
childrenContainer.appendChild(createTreeNode(child));
});
personDiv.appendChild(childrenContainer);
}

return personDiv;
}

const treeContainer = document.getElementById('tree');
treeContainer.appendChild(createTreeNode(sanjyraData));

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 20px;
}
.tree {
    display: flex;
    flex-direction: column;
    align-items: center;
}
.person {
    display: inline-block;
    margin: 10px;
    padding: 10px;
    border: 1px solid #000;
    border-radius: 5px;
    background-color:floralwhite;
}
.children {
    display: flex;
    gap: 10px;
    margin-top: 10px;
    
}
