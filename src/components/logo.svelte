<div>
  <h1 class="logo" data-content="HANS_">HANS_</h1>
  <div class="header-background" />
</div>

<style>
  div.header-background {
    background-color: #1b1b1b;
    margin: 0px 60px 0px 60px;
    height: 40px;
  }

  h1.logo {
    margin: 0;
    position: absolute;
    left: 7px;
    color: #ebebeb;
    letter-spacing: 5px;
  }

  h1.logo:after {
    margin: 0;
    content: attr(data-content);
    position: absolute;
    top: 0;
    left: 0;
    width: 1.8em;
    overflow: hidden;
    color: #1b1b1b;
  }
</style>
