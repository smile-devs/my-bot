<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080808">
<title>Bot Directory</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

:root{
  --bg:#070707;
  --panel:#101010;
  --panel-hover:#151515;
  --border:#252525;
  --text:#fff;
  --muted:#888;
}

html{
  scroll-behavior:smooth;
}

body{
  min-height:100vh;
  color:var(--text);
  background:
    radial-gradient(circle at 50% -15%,#222 0,transparent 38%),
    var(--bg);
  font-family:system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
  overflow-x:hidden;
}

body::before{
  content:"";
  position:fixed;
  inset:0;
  pointer-events:none;
  opacity:.15;
  background-image:
    linear-gradient(#fff 1px,transparent 1px),
    linear-gradient(90deg,#fff 1px,transparent 1px);
  background-size:70px 70px;
  mask-image:linear-gradient(to bottom,#000,transparent 75%);
}

.hero{
  max-width:1100px;
  margin:auto;
  padding:90px 24px 48px;
  animation:heroIn .8s cubic-bezier(.2,.8,.2,1);
}

.eyebrow{
  display:flex;
  align-items:center;
  gap:9px;
  color:#999;
  font-size:12px;
  letter-spacing:.14em;
  text-transform:uppercase;
  margin-bottom:20px;
}

.dot{
  width:6px;
  height:6px;
  border-radius:50%;
  background:#fff;
  box-shadow:0 0 14px #fff;
  animation:pulse 2s infinite;
}

h1{
  font-size:clamp(46px,8vw,82px);
  line-height:.95;
  letter-spacing:-.065em;
}

.hero p{
  max-width:570px;
  margin-top:22px;
  color:#858585;
  font-size:15px;
  line-height:1.8;
}

main{
  max-width:1100px;
  margin:auto;
  padding:0 24px 90px;
}

.search{
  width:100%;
  height:58px;
  padding:0 20px;
  border:1px solid var(--border);
  border-radius:16px;
  outline:none;
  color:#fff;
  background:rgba(15,15,15,.9);
  backdrop-filter:blur(15px);
  font-size:14px;
  transition:.25s;
  animation:fadeUp .7s .1s both;
}

.search::placeholder{
  color:#5f5f5f;
}

.search:focus{
  border-color:#444;
  box-shadow:0 0 0 4px rgba(255,255,255,.035);
}

.filters{
  display:flex;
  flex-wrap:wrap;
  gap:8px;
  margin:18px 0 28px;
  animation:fadeUp .7s .18s both;
}

.filter{
  border:1px solid #282828;
  border-radius:999px;
  padding:9px 14px;
  color:#888;
  background:#0d0d0d;
  cursor:pointer;
  font-size:12px;
  transition:.2s;
}

.filter:hover{
  color:#fff;
  border-color:#444;
  transform:translateY(-2px);
}

.filter.active{
  color:#000;
  background:#fff;
  border-color:#fff;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fill,minmax(300px,1fr));
  gap:15px;
}

.card{
  position:relative;
  padding:24px;
  overflow:hidden;
  border:1px solid #222;
  border-radius:22px;
  background:
    linear-gradient(145deg,#121212,#0d0d0d);
  animation:cardIn .65s cubic-bezier(.2,.8,.2,1) both;
  transition:
    transform .3s cubic-bezier(.2,.8,.2,1),
    border-color .3s,
    box-shadow .3s;
}

.card::before{
  content:"";
  position:absolute;
  top:-100%;
  left:-40%;
  width:50%;
  height:300%;
  transform:rotate(25deg);
  background:linear-gradient(
    90deg,
    transparent,
    rgba(255,255,255,.045),
    transparent
  );
  transition:left .7s;
  pointer-events:none;
}

.card:hover::before{
  left:120%;
}

.card:hover{
  transform:translateY(-7px);
  border-color:#3b3b3b;
  box-shadow:0 25px 60px rgba(0,0,0,.42);
}

.bot-head{
  display:flex;
  align-items:center;
  gap:15px;
}

.bot-icon{
  width:64px;
  height:64px;
  flex:none;
  display:grid;
  place-items:center;
  border:1px solid #303030;
  border-radius:18px;
  background:#181818;
  font-size:25px;
  font-weight:800;
  letter-spacing:-.06em;
  transition:.35s cubic-bezier(.2,.8,.2,1);
}

.card:hover .bot-icon{
  transform:rotate(-4deg) scale(1.06);
  border-color:#555;
}

.name{
  font-size:20px;
  font-weight:750;
  letter-spacing:-.03em;
}

.description{
  margin-top:5px;
  color:#858585;
  font-size:13px;
  line-height:1.6;
}

.tags{
  display:flex;
  flex-wrap:wrap;
  gap:6px;
  margin:20px 0;
}

.tag{
  padding:5px 9px;
  border:1px solid #242424;
  border-radius:7px;
  color:#999;
  background:#181818;
  font-size:10px;
}

.actions{
  display:flex;
}

.btn{
  width:100%;
  min-height:43px;
  display:flex;
  align-items:center;
  justify-content:center;
  border:1px solid #fff;
  border-radius:11px;
  color:#000;
  background:#fff;
  text-decoration:none;
  font-size:12px;
  font-weight:700;
  transition:.2s;
}

.btn:hover{
  transform:translateY(-2px);
  background:#e8e8e8;
}

.empty{
  display:none;
  padding:70px 0;
  color:#555;
  text-align:center;
}

footer{
  padding:30px 20px 45px;
  border-top:1px solid #151515;
  color:#505050;
  text-align:center;
  font-size:11px;
}

@keyframes heroIn{
  from{
    opacity:0;
    transform:translateY(25px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

@keyframes fadeUp{
  from{
    opacity:0;
    transform:translateY(12px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

@keyframes cardIn{
  from{
    opacity:0;
    transform:translateY(20px) scale(.97);
  }
  to{
    opacity:1;
    transform:translateY(0) scale(1);
  }
}

@keyframes pulse{
  0%,100%{
    opacity:.35;
    transform:scale(.8);
  }
  50%{
    opacity:1;
    transform:scale(1.15);
  }
}

@media(max-width:600px){
  .hero{
    padding-top:65px;
  }

  .grid{
    grid-template-columns:1fr;
  }
}

@media(prefers-reduced-motion:reduce){
  *,
  *::before,
  *::after{
    animation-duration:.01ms!important;
    transition-duration:.01ms!important;
  }
}
</style>
</head>

<body>

<header class="hero">
  <div class="eyebrow">
    <span class="dot"></span>
    Discord Bot Directory
  </div>

  <h1>Bot Directory</h1>

  <p>
    Discordサーバーをもっと便利にするBotを探そう。
    機能やカテゴリからBotを見つけられます。
  </p>
</header>

<main>

  <input
    id="search"
    class="search"
    type="search"
    placeholder="Bot名・説明・カテゴリを検索..."
    autocomplete="off"
  >

  <div id="filters" class="filters"></div>

  <section id="botList" class="grid"></section>

  <div id="empty" class="empty">
    該当するBotがありません。
  </div>

</main>

<footer>
  Discord Bot Directory
</footer>

<script>
const bots = [
  {
    name: "Aegis",
    description: "Discordを幅広く管理・便利にする万能ボット",
    clientId: "1555549472505991218",
    categories: [
      "Utility",
      "Moderation",
      "Management"
    ]
  }
];

const list = document.getElementById("botList");
const search = document.getElementById("search");
const filters = document.getElementById("filters");
const empty = document.getElementById("empty");

let currentCategory = "All";

const categories = [
  "All",
  ...new Set(bots.flatMap(bot => bot.categories))
];

for(const category of categories){
  const button = document.createElement("button");

  button.className =
    "filter" +
    (category === "All" ? " active" : "");

  button.textContent = category;

  button.addEventListener("click", () => {
    currentCategory = category;

    document
      .querySelectorAll(".filter")
      .forEach(element => {
        element.classList.remove("active");
      });

    button.classList.add("active");

    render();
  });

  filters.appendChild(button);
}

function escapeHtml(value){
  return String(value)
    .replaceAll("&","&amp;")
    .replaceAll("<","&lt;")
    .replaceAll(">","&gt;")
    .replaceAll('"',"&quot;")
    .replaceAll("'","&#039;");
}

function getInviteUrl(clientId){
  return (
    "https://discord.com/oauth2/authorize" +
    "?client_id=" +
    encodeURIComponent(clientId) +
    "&scope=bot%20applications.commands"
  );
}

function render(){
  const keyword =
    search.value
      .toLowerCase()
      .trim();

  const result = bots.filter(bot => {
    const text = [
      bot.name,
      bot.description,
      ...bot.categories
    ]
      .join(" ")
      .toLowerCase();

    const matchesSearch =
      text.includes(keyword);

    const matchesCategory =
      currentCategory === "All" ||
      bot.categories.includes(currentCategory);

    return matchesSearch && matchesCategory;
  });

  list.innerHTML = "";

  result.forEach((bot,index) => {
    const card = document.createElement("article");

    card.className = "card";
    card.style.animationDelay = `${index * 70}ms`;

    card.innerHTML = `
      <div class="bot-head">
        <div class="bot-icon">A</div>

        <div>
          <div class="name">
            ${escapeHtml(bot.name)}
          </div>

          <div class="description">
            ${escapeHtml(bot.description)}
          </div>
        </div>
      </div>

      <div class="tags">
        ${bot.categories.map(category => `
          <span class="tag">
            ${escapeHtml(category)}
          </span>
        `).join("")}
      </div>

      <div class="actions">
        <a
          class="btn"
          href="${getInviteUrl(bot.clientId)}"
          target="_blank"
          rel="noopener noreferrer"
        >
          招待する
        </a>
      </div>
    `;

    list.appendChild(card);
  });

  empty.style.display =
    result.length ? "none" : "block";
}

search.addEventListener("input", render);

render();
</script>

</body>
</html>
