
<div class="macintosh" aria-label="1984 Macintosh illustration">
    <div class="monitor">
      <div class="monitor-inner">
        <div class="screen-cutout">
          <div class="screen">
            <div class="banner">
                <img src="https://www.curseforge.com/Content/2-0-8408-34225/Skins/CurseForge/images/anvil.svg" alt='curseforge'/>
            </div>

            <div class="downloads">
                <div class="file"/>
                <div class="file"/>
            </div>
          </div>
        </div>
        <div class="logo">
          <p>🏳️‍🌈</p>
        </div>
        <div class="opening">
          <div class="opening-inner">
          </div>
        </div>
      </div>
    </div>
    <div class="foot">
      <div class="inset"></div>
        <div class="cable-container">
            <div class="cable-hole"></div>
        </div>
    </div>
</div>

<style lang="scss">
    .macintosh {
        display: block;
        width: 340px;
        height: 475px;
        margin: 125px auto;
        position: relative;
        box-shadow: 0 80px 60px -60px rgba(0,0,0,0.4);
        font-family: 'Minecraftia';
    }

    .monitor {
        z-index: 2;
        display: block;
        width: 100%;
        height: 410px;
        border-radius: 15px;
        background-color: #DDDBC2;
        position: absolute;
        background-image: lineear-gradient(
            #DDDBC2, #DFDAC4
        );
        background-image: conic-gradient(
            #DDDBC2 0 10.5%, #ECECD5 11% 11.5%, #CECDAF 12% 38%, #C8C4A7 39% 61.5%, #C7C3A6 62% 88%, #DFDAC4 88.5% 89%, #DDDBC2 89.25%
        ); /* Not supported everywhere :( */
        box-shadow: 0 60px 20px -20px rgba(142,137,97,0.5);
    }

    .monitor-inner {
        display: block;
        width: 320px;
        height: 360px;
        background-image: linear-gradient(#CAC6A9, #CFCEB0);
        margin: auto;
        position: absolute;
        top: 22px;
        left: 0;
        right: 0;
        border-radius: 5px;
    }

    .screen-cutout {
        display: block;
        width: 280px;
        height: 225px;
        background-color: #DDDBC2;
        margin: auto;
        position: absolute;
        left: 0;
        right: 0;
        top: 20px;
        border-radius: 5px;
        background-image: linear-gradient(
            #938F6A, #E0DFC3
        ); 
        background-image: conic-gradient(
            #938F6A 12.5%, #B5B293 15.5% 33%, #E0DFC3 34% 65.5%, #C2C1A2 66.5% 83.5%, #938F6A 86.5%
        ); 
    }

    .screen {
        display: block;
        width: 260px;
        height: 195px;
        border-radius: 20px;
        box-shadow: 0 0 30px 10px #464444ee inset;
        background-image: radial-gradient(#c5c5d1, #e1eef2);
        color: black;

        > .banner {
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            height: 30px;
            background-color: #181914aa;
            color: #c5c5d1;
            display: flex;
            z-index: 1;
        }

        > .banner > img {
            z-index: 1;
            margin-top: auto;
            margin-bottom: auto;
            margin-left: 10px;
            height: 13px;
        }

        > .downloads {
            background-color: #c5c5d133;
            box-shadow: 5px 5px 10px 1px #46444444;
            width: 90%;
            height: 100px;
            margin: auto;
            margin-top: 20px;
            border-radius: 10px;
        }

        .downloads > .file {
            width: 80%;
            height: 2em;
            margin: auto;
            margin-top: 10px;
            background-color: #c5c5d133;
            box-shadow: 5px 5px 10px 1px #46444444;
        }
    }

    .logo {
        display: block;
        width: 22px;
        height: 22px;
        background-image: radial-gradient(#C9C6B5, #CBC9BA);
        border-radius: 2px;
        position: absolute;
        left: 22px;
        bottom: 22px;
        padding-left: 3.5px;
        box-shadow: 0 0 2px 0px #979181 inset;
    }

    .logo p {
        text-align: center;
        margin-top: -2px;
    }

    .opening {
        display: block;
        width: 155px;
        height: 15px;
        background-image: linear-gradient(
            #BEBB9C, #CAC8A7 74.5% 75.5%);
        background-image: conic-gradient(
            #BEBB9C 0% 23.5%, #C7C2A2 24.5% 25%, #DCD8BD 26% 73.5%, #CAC8A7 74.5% 75.5%, #BEBB9C 76.5%);
        position: absolute;
        bottom: 55px;
        right: 21px;
        border-radius: 4px;
    }

    .opening-inner {
        display: block;
        width: 126px;
        height: 8px;
        background-color: #181914;
        border-radius: 2px;
        margin: auto;
        position: absolute;
        left: 0;
        right: 0;
        top: 3.5px;
    }

    .foot {
        display: block;
        width: 100%;
        height: 85px;
        position: absolute;
        bottom: 0;
        left: 0;
        z-index: 1;
        border-radius: 7px;
        background-image: linear-gradient(#BBB497, #C1BE9F);
        box-shadow: 14px 0 3px -7px #CCCAB1 inset,
            -14px 0 3px -7px #CECDB1 inset,
            0 32px 3px -7px #C1BE9F inset,
            0 -6px 3px -4px #AEAA87 inset; 
    }

    .inset {
        display: inline;
        width: 16px;
        height: 16px;
        background-color: #C3BEA0;
        position: absolute;
        bottom: 20px;
        left: 35px;
        border-radius: 2px;
        box-shadow: 0 0 2px #C9C3A3 inset,
            0 0px 2px 1px #BCB694;
    }

    .cable-container {
        display: block;
        width: 60px;
        height: 30px;
        background-color: #C3BEA0;
        position: absolute;
        right: 30px;
        bottom: 15px;
        border-radius: 3px;
        box-shadow: 0 2px 1px -1px #D0CBAE inset,
            4px 0 1px -1px #BAB492 inset,
            -5px 0 2px -2px #A8A281 inset,
            0 -4px 2px -3px #ADA88B inset;;
    }

    .cable-hole {
        display: block;
        width: 18px;
        height: 20px;
        background-color: #848580;
        position: absolute;
        top: 5px;
        right: 7px;
        border-radius: 3px;
        box-shadow: 0 -4px 0.5px -0.5px rgba(25,25,25,0.2) inset,
            -2px 0 0.5px -0.5px rgba(25,25,25,0.2) inset,
            2px 0 0.5px -0.5px rgba(25,25,25,0.2) inset;
        background-image: linear-gradient(
            #848580 20%,
            transparent 20% 80%,
            #848580 80%
        ), linear-gradient(
            90deg,
            transparent 30%,
            #181914 30% 70%,
            transparent 70%
        );
    }
</style>