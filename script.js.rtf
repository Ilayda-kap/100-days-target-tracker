{\rtf1\ansi\ansicpg1252\cocoartf2761
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 const goals = [\
    "Drikke 6 glas vand",\
    "Spise mindre usundt",\
    "Lave shots",\
    "Posture check",\
    "Kigge p\'e5 telefon max. 3 timer",\
    "L\'e6se mindst 30 sider bog hver uge",\
    "Ikke stalke",\
    "G\'e5 tur i mindst 20 min.",\
    "L\'e6se koran mindst 1 side",\
    "Lave 1000 taba",\
    "Lave 1000 shukr",\
    "Lave 700 salawat"\
];\
\
let completedGoals = [];\
\
function createGoalElements() \{\
    const container = document.getElementById('goals-container');\
    container.innerHTML = '';\
\
    goals.forEach((goal, index) => \{\
        const goalDiv = document.createElement('div');\
        goalDiv.classList.add('goal');\
        goalDiv.innerHTML = `\
            <h3>$\{goal\}</h3>\
            <button onclick="toggleGoal($\{index\}, true)">\uc0\u10004 </button>\
            <button onclick="toggleGoal($\{index\}, false)">\uc0\u10006 </button>\
        `;\
        container.appendChild(goalDiv);\
    \});\
\}\
\
function toggleGoal(index, completed) \{\
    if (completed) \{\
        if (!completedGoals.includes(index)) \{\
            completedGoals.push(index);\
        \}\
    \} else \{\
        const idx = completedGoals.indexOf(index);\
        if (idx !== -1) \{\
            completedGoals.splice(idx, 1);\
        \}\
    \}\
\
    updateStatus();\
\}\
\
function updateStatus() \{\
    const status = document.getElementById('status');\
    const totalGoals = goals.length;\
    const completed = completedGoals.length;\
\
    let smiley = '';\
    let message = '';\
\
    if (completed <= 3) \{\
        smiley = '\uc0\u55357 \u56865 ';\
        message = 'P\'e5 vej til orange';\
    \} else if (completed <= 6) \{\
        smiley = '\uc0\u55357 \u56898 ';\
        message = 'P\'e5 vej til gul';\
    \} else if (completed <= 9) \{\
        smiley = '\uc0\u55357 \u56842 ';\
        message = 'P\'e5 vej til gr\'f8n, godt p\'e5 vej!';\
    \} else \{\
        smiley = '\uc0\u55357 \u56836 ';\
        message = 'Godt klaret, bliv ved med denne indsats!';\
    \}\
\
    status.innerHTML = `\
        <div class="smiley">$\{smiley\}</div>\
        <p>$\{completed\} ud af $\{totalGoals\} m\'e5l udf\'f8rt. $\{message\}</p>\
    `;\
\}\
\
document.getElementById('nextDayButton').addEventListener('click', () => \{\
    completedGoals = [];\
    createGoalElements();\
    updateStatus();\
\});\
\
createGoalElements();\
updateStatus();\
}