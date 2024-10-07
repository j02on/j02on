<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      .line {
        background-color: rgb(179, 179, 179);
        border: none;
        height: 1px;
      }
      .stackAll {
        display: flex;
        flex-direction: column;
        gap: 10px;
        padding-left: 10px;
      }
      .stackTitle {
        font-size: 24px;
        font-weight: 600;
      }
      .stackContents {
        display: flex;
        flex-direction: column;
        gap: 5px;
      }

      .statsContents {
        display: flex;
        flex-direction: column;
        gap: 30px;
      }

      .all {
        width: 100vw;
        display: flex;
        justify-content: left;
        gap: 100px;
      }

      a {
        text-decoration: none;
        color: black;
      }

      * {
        font-family: 'MaruBuri';
      }

@font-face {
font-family: 'MaruBuri';
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Regular.eot);
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Regular.eot?#iefix) format("embedded-opentype"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Regular.woff2) format("woff2"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Regular.woff) format("woff"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Regular.ttf) format("truetype");
}

@font-face {
font-family: 'MaruBuriSemiBold';
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-SemiBold.eot);
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-SemiBold.eot?#iefix) format("embedded-opentype"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-SemiBold.woff2) format("woff2"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-SemiBold.woff) format("woff"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-SemiBold.ttf) format("truetype");
}

@font-face {
font-family: 'MaruBuriBold';
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Bold.eot);
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Bold.eot?#iefix) format("embedded-opentype"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Bold.woff2) format("woff2"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Bold.woff) format("woff"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Bold.ttf) format("truetype");
}

@font-face {
font-family: 'MaruBuriLight';
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Light.eot);
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Light.eot?#iefix) format("embedded-opentype"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Light.woff2) format("woff2"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Light.woff) format("woff"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-Light.ttf) format("truetype");
}

@font-face {
font-family: 'MaruBuriExtraLight';
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-ExtraLight.eot);
src: url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-ExtraLight.eot?#iefix) format("embedded-opentype"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-ExtraLight.woff2) format("woff2"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-ExtraLight.woff) format("woff"), url(https://hangeul.pstatic.net/hangeul_static/webfont/MaruBuri/MaruBuri-ExtraLight.ttf) format("truetype");
}
</style>

  </head>
  <body>
    <div>
      <h1>Hello! I am Jiyeon Park, growing every day.😊</h1>
      <p>I am studying hard as a front-end developer.</p>
      <hr class="line" />
      <div class="all">
        <div class="stackAll">
          <p class="stackTitle">⚙️ stack</p>
          <div class="stackContents">
            <div>html</div>
            <div>css</div>
            <div>javascript</div>
            <div>typescript</div>
            <div>react js</div>
            <div>styled-components</div>
            <div>react-router-dom</div>
            <div>vite</div>
            <div>figma</div>
            <div>c</div>
          </div>
        </div>
      <div class="stackAll">
          <p class="stackTitle">⭐️ link</p>
          <div class="stackContents">
            <a target="_blank" href="https://www.instagram.com/h_yy.0n/">instargram</a>
            <a target="_blank" href="https://www.facebook.com/profile.php?id=61557320422273">facebook</a>
            <a target="_blank" href="https://velog.io/@pjylove08/posts">velog</a>
          </div>
        </div>
        <div class="stackAll">
          <p class="stackTitle">⭐️ stats</p>
          <div class="statsContents">
            <img src="https://github-readme-stats.vercel.app/api?username=j02on&bg_color=60,ffffff,ffffff&title_color=000000&text_color=000000"/>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=j02on&layout=compact&bg_color=60,ffffff,ffffff&title_color=000000&text_color=000000"/>
          </div>
        </div>
      </div>
    </div>
    </div>
    <script></script>
  </body>
</html>
