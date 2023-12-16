<template>
  <div class="hello">
    <div class="box">
      <div class="head">
        <img src="../assets/2.png">
        <div class="head_one">
          <p><a href="https://booski.vercel.app/#/">Home</a></p>
          <p><a href="#one"> Partners</a></p>
          <p> <a href="#two">About</a></p>
          <p> <a href="#three">Tokenomics</a></p>
          <p> <a href="#four">Roadmap</a></p>
          <p> <a href="https://github.com/cyberscope-io/audits/blob/main/booskie/audit.pdf">Audit</a></p>
          <p> <a href="https://github.com/SecureBe/Audit-KYC/blob/main/Booskie%20KYC.pdf">KYC</a></p>
          <p><a href="#five">FAQs</a></p>
          <p><a target="_blank" href="https://booski.vercel.app/#/about">Stake</a></p>
          <p><a href="#seve">Contact</a></p>
          <p style="cursor: grabbing;" @click="add">Connect</p>
        </div>
      </div>
      <div class="cen">
        <div class="cen_1">
          <img class="cen_img" src="../assets/1.png">
          <div class="cen_2">
            <a href="https://twitter.com/BooskieToken"><img src="../assets/tb_1.png"></a>
            <a href="https://t.me/booskie"><img src="../assets/tb_2.png"></a>
            <a href="https://www.facebook.com/profile.php?id=100094243596985"><img src="../assets/tb_3.png"></a>
            <a href="https://discord.gg/w4p4WqJFsE"><img src="../assets/tb_4.png"></a>
            <a href="#"><img src="../assets/tb_5.png"></a>
            <a href="#"><img src="../assets/tb_6.png"></a>
            <a href="#"><img src="../assets/tb_7.png"></a>
          </div>
          <div class="cen_3">
            <div v-if="nr">
              Copied to Clipboard
            </div>
            <div @click="txt" v-else>
              0xe1C076D22524Ed30829A45546C3A29f69a2712F4
            </div>
          </div>
        </div>
        <div class="cen_4" id="one">
          <h1>PARTNERS</h1>
          <div class="cen_5">
            <div class="cen_tp"><a href="https://www.dexview.com/eth/0xe1C076D22524Ed30829A45546C3A29f69a2712F4"><img
                  src="../assets/3.png"></a></div>
            <div class="cen_tp1"><a
                href="https://etherscan.io/token/0xe1c076d22524ed30829a45546c3a29f69a2712f4?a=0xb14e3d7b58a74bda900387ae19a047a292505d04"><img
                  src="../assets/4.png"></a></div>
            <div class="cen_tp2"><a href="https://uniswap.org/"><img src="../assets/5.png"></a></div>
            <div class="cen_tp3"><a
                href="https://www.dextools.io/app/en/ether/pair-explorer/0xe1C076D22524Ed30829A45546C3A29f69a2712F4"><img
                  src="../assets/6.png"></a></div>
            <div class="cen_tp4"><a
                href="https://app.bubblemaps.io/eth/token/0xe1C076D22524Ed30829A45546C3A29f69a2712F4"><img
                  src="../assets/7.png"></a></div>
            <div class="cen_tp5"><a
                href="https://www.pinksale.finance/launchpad/0x7A27db6F842bD155128fF863De60b3A5bBA47c8f?chain=ETH"><img
                  src="../assets/8.png"></a></div>
          </div>
          <div class="cen_6">
            <div class="cen_tp6"><a href="https://www.coingecko.com/"><img src="../assets/9.png"></a></div>
            <div class="cen_tp7"><a href="https://coinmarketcap.com/"><img src="../assets/10.png"></a></div>
          </div>
        </div>
      </div>
      <div class="xmao">
        <div class="xmo">
          <div class="wave-div"></div>
          <div class="xmd" id="two">
            <div class="xmd_one">
              <div class="xmd_two">
                <img src="../assets/11.png">
                <a target="_blank" href="https://github.com/SecureBe/Audit-KYC/blob/main/Booskie%20KYC.pdf">
                  <img class="xmd_tp" src="../assets/15.png">
                </a>
              </div>
              <div class="xmd_thre">
                <h1>ABOUT
                  BooSkie</h1>
                <p>Experience the revolution of laughter and decentralized finance with Booskie, the meme token built on
                  the Ethereum blockchain. Hold onto your Booskie tokens for a journey filled with humor, community
                  engagement, and financial empowerment. Join us today and let’s spread joy, one meme at a time!</p>
                <a href="https://github.com/cyberscope-io/audits/blob/main/booskie/audit.pdf">
                  <img src="../assets/12.png">
                </a>

              </div>
            </div>
          </div>divs
          <div class="wave-divs"></div>
        </div>
      </div>
      <div class="pink">
        <div class="pink_one" id="three">
          <h1>HOW TO BUY</h1>
          <span>Hold on for Dear Love</span>
          <div class="pink_1">
            <div class="pink_two">
              <p> 0xe1C076D22524Ed30829A45546C3A29f69a2712F4</p>
              <span>CONTRACT ADDRESS</span>
            </div>
            <div class="pink_three">
              <h1>Create a Wallet</h1>
              <p>Download MetaMask or your wallet of choice from the app store or Google Play store for free. Desktop
                users, download the Google chrome extension by going to metamask.io.</p>
            </div>
          </div>
          <div class="pink_four">
            <div class="pink_four_1">
              <h1>Get Some ETH</h1>
              <p>Have ETH in your wallet to switch to $BOOSKIE. If you don’t have any ETH, you can buy directly on
                MetaMask, transfer from another wallet, or buy on another exchange and send it to your wallet.</p>
            </div>
            <div class="pink_four_2">
              <h1>Go to Uniswap</h1>
              <p>Connect to Uniswap. Go to app.uniswap.org in Google Chrome or on the browser inside your MetaMask.app.
                Connect your wallet. Paste the $BOOSKIE token address into Uniswap, select Pepe, and confirm. When
                MetaMask prompts you for a wallet signature, sign.</p>
            </div>
            <div class="pink_four_3">
              <h1>SWAP ETH for $BOOSKIE</h1>
              <p>Swap ETH for $BOOSKIE. We have ZERO taxes so you don’t need to worry about buying with a specific
                slippage, although you may need to use slippage during times of market volatility.</p>
            </div>
          </div>
        </div>
        <div class="wave-divs"></div>
        <div class="pink_ones">
          <h1 style="color: rgb(234, 41, 99);">TOKENOMICS</h1>
          <span style="color: rgb(234, 41, 99);">Hold on for Dear Love</span>
          <div class="pink_1">
            <div class="pink_two">
              <p> 0xe1C076D22524Ed30829A45546C3A29f69a2712F4</p>
              <span>CONTRACT ADDRESS</span>
            </div>
            <div class="pink_three">
              <h1>1 Trillion</h1>
              <p style="text-align: center;">TOTAL SUPPLY</p>
            </div>
          </div>
          <div class="pink_four">
            <div class="pink_four_1">
              <h1>94% Liquidity</h1>
              <p>94% of the tokens will be sent to the liquidity pool (LP) when the token is launched. LP tokens will be
                burnt, and the contract will be renounced.</p>
            </div>
            <div class="pink_four_2">
              <h1>0% Taxes & Fees</h1>
              <p>No Taxes and Fees during Presale.</p>
            </div>
            <div class="pink_four_3">
              <h1>4% CEX Listing, Marketing & Future Development</h1>
              <p>Help us to Develop the Booskie Token further and bring new features and DAPPs that will help us stand out
                from the rest.
              </p>
              <p>
                The remaining 4% of the supply is being held in a multi-sig wallet only to be used as tokens for future
                centralized exchange listings, bridges, and liquidity pools.</p>
            </div>
          </div>
        </div>
      </div>
      <div class="road">
        <div class="road_one" id="four">
          <h1>ROADMAP</h1>
          <span>Hold on for Dear Love</span>
        </div>
        <div class="road_ones">
          <div class="road_two">
            <h1>PHASE 1</h1>
            <li>Website Development✅</li>
            <li>Whitepaper✅</li>
            <li>Contract Verified on BSCScan✅</li>
            <li>1M MarketCap🚧</li>
            <li>Listing Mexc🚧</li>
            <li>5M MarketCap 🚧</li>
            <li>10M MarketCap 🚧</li>
            <li>15M MarketCap 🚧</li>
            <li>25M MarketCap 🚧</li>
            <li>CoinGecko Listing🚧</li>
            <li>CoinMarketCap Listing🚧</li>
          </div>
          <div class="road_three">
            <h1>PHASE 2</h1>
            <li>CoinGecko Listing🚧</li>
            <li>Marketing to influencers🚧</li>
            <li>Listing Bitmart🚧</li>
            <li>Audit✅</li>
            <li>Merch🚧</li>
            <li>Listing Gateio🚧</li>
            <li>more cex…..🚧</li>
            <li>EtherScan Update (Logo, TG, Twitter, Website)🚧</li>
            <li>5,000 Holders🚧</li>
            <li>5,000 Telegram Members🚧</li>
            <li>10,000 Holders🚧</li>
            <li>110,000 Telegram Members🚧</li>
            <li>Marketing Campaign🚧</li>
          </div>
          <div class="road_four">
            <h1>PHASE 3</h1>
            <li>BooSkie Wallet 🚧</li>
            <li>More CEX listings🚧</li>
            <li>Further Marketing & Development🚧</li>
            <li>BooSkie BuyBack & Burn Event🚧</li>
            <li>15,000 Telegram Members🚧</li>
            <li>30,000 Holders🚧</li>
            <li>100M MarketCap🚧</li>
            <li>BooSkie (NFT Marketplace)🚧</li>
            <li>500M MarketCap🚧</li>
            <li>1,000,000 Holders🚧</li>
            <li>BooSkie DEX🚧</li>
            <li>1B MarketCap🚧</li>
            <li>Influencer Awareness Partnerships🚧</li>
          </div>
        </div>
        <div class="wave-divsx"></div>
        <div class="wave-divsd"></div>
        <div class="xm_ann">
          <div class="xm_aone">
            <div class="xm_atwo">
              <h1>PINKPAPER</h1>
              <p>Welcome to the Booskie Pinkpaper, where we unveil the extraordinary potential of memes in the world of
                decentralized finance (DeFi). In this comprehensive document, we present a revolutionary concept that
                combines the viral nature of memes with the transparency and security of blockchain technology.</p>
              <div><a target="_blank"
                  href="https://booskie.com/wp-content/uploads/2023/07/Booskie-Pinkpaper-2023.pdf">Whitepaper</a></div>
            </div>
          </div>
          <div class="xm_three">
            <img src="../assets/1.png">
          </div>
        </div>
        <div class="wave-divsds"></div>
      </div>
      <div class="clog" id="five">
        <h1>FAQs</h1>
        <div class="clong">
          <div class="cong_1">
            <p class="clong_one" @click="toggleContent">What do Booskie mean?</p>
            <p class="clong_two" v-show="isExpanded">
              Booskie is a term of endearment for a significant other. A booskie is more intimate than a boo. It refers to
              your lover being your best friend.
            </p>
            <p class="clong_one" @click="toggleContent1">What is the contract addresss?</p>
            <p class="clong_two" v-show="isExpanded1">
              0xe1C076D22524Ed30829A45546C3A29f69a2712F4
            </p>
            <p class="clong_one" @click="toggleContent2">How can I securely store my Booskie tokens?</p>
            <p class="clong_two" v-show="isExpanded2">
              To securely store your Booskie tokens, you’ll need an Ethereum-compatible wallet. Popular options include
              MetaMask, Trust Wallet, and Ledger Nano hardware wallets. These wallets provide a secure environment to
              store and manage your tokens. Remember to keep your private keys or recovery phrases safe and never share
              them with anyone.
            </p>
            <p class="clong_one" @click="toggleContent3">What is Booskie's roadmap for the future?</p>
            <p class="clong_two" v-show="isExpanded3">
              Booskie has an exciting roadmap ahead. While we can’t reveal all the details just yet, we are actively
              exploring partnerships and collaborations to expand the utility and use cases of Booskie. Our future plans
              include exploring decentralized applications (DApps), venturing into the world of non-fungible tokens
              (NFTs), and continuously enhancing the overall user experience. Stay tuned to our official announcements for
              updates on upcoming developments.
            </p>
          </div>
        </div>
        <div class="wave-divsdsb"></div>
        <div class="button" id="seve">
          <h1>EXPLORE
            <br>
            BooSkie
          </h1>
          <p>$BOOSKIE is a meme coin with no intrinsic value or expectation of financial return. It is simply a meme coin
            to HODL (Hold on for Dear Love). There is no formal team or utilities. The coin is completely useless and for
            entertainment purposes only. But things can change in the future?</p>
          <div class="but_2">
            <a href="https://twitter.com/BooskieToken"><img src="../assets/tb_1.png"></a>
            <a href="https://t.me/booskie"><img src="../assets/tb_2.png"></a>
            <a href="https://www.facebook.com/profile.php?id=100094243596985"><img src="../assets/tb_3.png"></a>
            <a href="https://discord.gg/w4p4WqJFsE"><img src="../assets/tb_4.png"></a>
            <a href="#"><img src="../assets/tb_5.png"></a>
            <a href="#"><img src="../assets/tb_6.png"></a>
            <a href="#"><img src="../assets/tb_7.png"></a>
          </div>
          <div class="but_one">
            <a href="https://github.com/SecureBe/Audit-KYC/blob/main/Booskie%20KYC.pdf">
              <img class="but_o1" src="../assets/15.png">
            </a>
            <a href="https://github.com/cyberscope-io/audits/blob/main/booskie/audit.pdf">
              <img class="but_o2" src="../assets/12.png">
            </a>
          </div>
          <div class="but_two">
            info@booskie.com
            <br>
            BooSkie 2023 - All Rights Reserved
          </div>
        </div>
        <div class="wave-divsboxd"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      nr: false,
      isExpanded: false,
      isExpanded1: false,
      isExpanded2: false,
      isExpanded3: false,
    };
  },
  methods: {
    to() {
      this.$router.push('/about');
    },
    add(){
      main();
    },
    txt() {
      this.nr = !this.nr;
      // 使用 setTimeout 在两秒后再次切换回原始内容
      console.log(111)
      setTimeout(() => {
        this.nr = false;
      }, 2000);
    },
    toggleContent() {
      this.isExpanded = !this.isExpanded;
    },
    toggleContent1() {
      this.isExpanded1 = !this.isExpanded1;
    },
    toggleContent2() {
      this.isExpanded2 = !this.isExpanded2;
    },
    toggleContent3() {
      this.isExpanded3 = !this.isExpanded3;
    }
  }
}
</script>
<style scoped lang="scss">
@font-face {
  font-family: 'one';
  src: url('../assets/one.woff2') format('truetype');
}

@font-face {
  font-family: 'two';
  src: url('../assets/two.woff2') format('truetype');
}

@font-face {
  font-family: 'three';
  src: url('../assets/three.woff2') format('truetype');
}

@font-face {
  font-family: 'four';
  src: url('../assets/four.woff2') format('truetype');
}

* {
  margin: 0;
  padding: 0;
}

.box {
  width: 100%;
  // height: 60rem;
  background-image: url('../assets/17.jpg');
  // background-size: 100% 100%;
  // background-repeat: no-repeat;
}

.head {
  width: 100%;
  // height: 8rem;
  background-color: rgba(245, 139, 159, 0.6);
  display: flex;
  justify-content: space-between;
  align-items: center;

}

.head>img {
  width: 80px;
  height: 80px;
  margin-left: 2.5rem;
}

.head_one {
  display: flex;
  color: white;
  width: 48rem;
  margin-right: 3rem;
  justify-content: space-between;
  font-family: four;
  font-size: 16px;
  margin-right: 5rem;
  height: 8rem;
  align-items: center
}

.head_one>p>a {

  color: white;
}

.cen {
  width: 100%;
  // height: 0rem;
  // border: 1px red solid;
  padding-bottom: 12rem;
}

.pink_three:hover {
  border: 2px white dashed;
}

.pink_four>div:hover {
  border: 2px white dashed;
}

.road_ones>div:hover {
  border: 2px white dashed;
}

.xm_atwo:hover {
  border: 2px white dashed;
}

.cen_1 {
  width: 60%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.cen_img {
  margin-top: 3rem;
  width: 580px;
  height: 580px;
}

.cen_2 {
  // width: 80%;
  display: flex;
  margin: 2rem 0 1rem 0;
}

.cen_2>a {
  margin-left: 1rem;
}

.cen_2>a>img {
  width: 60px;
  height: 60px;
}

.cen_3 {
  width: 60%;
  background-color: rgb(235, 42, 100);
  text-align: center;
  padding: 1rem;
  border-style: dashed;
  border-width: 2px;
  border-style: dashed;
  border-color: white;
  color: white;
  margin-bottom: 5rem
}

.cen_4 {
  width: 80%;
  margin: 0 auto;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.cen_4>h1 {
  font-family: three;
  color: white;
  font-size: 108px;
  text-align: center;
  text-shadow: 0px 0px 17px #FF009C;
}

.cen_5 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.cen_5>div {
  border: 2px red solid;
  margin-bottom: 2rem;
}

.cen_tp {
  width: 30%;
  height: 6rem;
  background-color: white;
  border: 1px red solid;
  border-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cen_tp>a>img {
  width: 300px;
  height: 70px;
}

.cen_tp1 {
  width: 30%;
  height: 6rem;
  background-color: white;
  border: 1px red solid;
  border-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cen_tp1>a>img {
  width: 300px;
  height: 70px;
}

.cen_tp2 {
  width: 30%;
  height: 6rem;
  background-color: white;
  border: 1px red solid;
  border-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cen_tp2>a>img {
  width: 300px;
  height: 70px;
}

.cen_tp3 {
  width: 30%;
  height: 6rem;
  background-color: white;
  border: 1px red solid;
  border-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cen_tp3>a>img {
  width: 300px;
  height: 70px;
}

.cen_tp4 {
  width: 30%;
  height: 6rem;
  background-color: white;
  border: 1px red solid;
  border-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cen_tp4>a>img {
  width: 271px;
  height: 101px;
}

.cen_tp5 {
  width: 30%;
  height: 6rem;
  background-color: white;
  border: 1px red solid;
  border-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cen_tp5>a>img {
  width: 250px;
  height: 82px;
}

.cen_6 {
  width: 100%;
  display: flex;
  justify-content: space-around;
}

.cen_6>div {
  width: 47%;
  height: 6rem;
  background-color: white;
  border: 2px red solid;
  border-radius: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cen_5>div:hover {
  border-style: dashed;

}

.cen_6>div:hover {
  border-style: dashed;
}

// .wave-div {
//   // width: 400px;
//   height: 400px;
//   // outline: 2px dashed gray;
//   --c: rgba(234, 41, 99);
//   --w1: radial-gradient(100% 57% at top, #0000 100%, var(--c) 100.5%) no-repeat;
//   --w2: radial-gradient(100% 57% at bottom, var(--c) 100%, #0000 100.5%) no-repeat;
//   background: var(--w1), var(--w2), var(--w1), var(--w2);
//   background-position-x: -200%, -100%, 0%, 100%;
//   background-position-y: 100%;
//   background-size: 50.5% 100%;
//   animation: m 1s infinite linear;

// }

// @keyframes m {
//   0% {
//     background-position-x: -200%, -100%, 0%, 100%
//   }

//   100% {
//     background-position-x: 0%, 100%, 200%, 300%
//   }
// }

// .wave-divs {
//   // width: 400px;
//   height: 400px;
//   // outline: 2px dashed gray;
//   --c: rgba(234, 41, 99);
//   --w1: radial-gradient(100% 57% at top, #0000 100%, var(--c) 100.5%) no-repeat;
//   --w2: radial-gradient(100% 57% at bottom, var(--c) 100%, #0000 100.5%) no-repeat;
//   background: var(--w1), var(--w2), var(--w1), var(--w2);
//   background-position-x: -200%, -100%, 0%, 100%;
//   background-position-y: 100%;
//   background-size: 50.5% 100%;
//   animation: m 1s infinite linear;
//   display: flex;

// }
.wave-div {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: relative;
  top: -13%;
}

.wave-divs {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: relative;
  top: 6%;
}


.wave-divsx {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: absolute;
  top: -19%;
}

.wave-divsd {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: absolute;
  top: 42%;
}

.wave-divsds {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: absolute;
  top: 90%;
}

.wave-divsdsb {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  // position: absolute;
  position: relative;
  top: 3%;
}

.wave-divsboxd {
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: relative;
  // top: 3%; 
}

.xmao {
  // max-width:1800px ;
}

.xmo {
  width: 100%;
  background-color: white;
  height: 80rem;
  // background-color:pink;
}

.xmd {
  width: 80%;
  // height: 12rem;
  display: flex;
  margin: 0 auto;
  background-color: white;

}

.xmd_one {
  display: flex;
}

.xmd_two {
  width: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.xmd_tp {
  width: 322px;
  height: 208px;
}

.xmd_thre {
  width: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
  color: rgb(234, 41, 99);
}

.xmd_thre>h1 {
  font-size: 90px;
  font-family: three;
  line-height: 85px;
  text-align: center;
  margin-bottom: 2rem;
}

.xmd_thre>p {
  font-family: two;
  opacity: 0.8;
  font-size: 24px;
  line-height: 40px;
  text-align: center;
  margin-bottom: 2rem;
}

.xmd_thre>a>img {
  width: 405px;
  height: 145px;
}

.pink {
  width: 100%;
  // height: 60rem;
  background-image: url('../assets//16.jpg');
  // background-size: 100% 100%;
  padding-bottom: 10rem;
}

.pink_one {
  width: 80%;
  margin: 0 auto;
  padding-top: 8rem;
  text-align: center;
}

.pink_one>h1 {
  font-size: 66px;
  font-family: three;
  color: #4F62BB;
}

.pink_one>span {
  // font-size: 66px;
  // font-family: three;
  color: #29C4EA;
}

.pink_ones {
  width: 80%;
  margin: 0 auto;
  padding-top: 0rem;
  text-align: center;
}

.pink_ones>h1 {
  font-size: 66px;
  font-family: three;
  color: #4F62BB;
}

.pink_ones>span {
  // font-size: 66px;
  // font-family: three;
  color: #29C4EA;
}


.pink_1 {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.pink_two {
  margin-top: 2rem;
  width: 80%;
  padding: 1.5rem;
  border-radius: 15px;
  color: white;
  background-color: rgb(234, 41, 99);
  // margin: 0 auto;
  font-family: one;
  font-size: 20px;
  border: 2px white solid;
}

.pink_two:hover {
  border-style: dashed;
}

.pink_two>p {
  font-size: 26px;
}

.pink_two>span {
  display: block;
  // margin-top: 1rem;
  margin-top: 10px;
}

.pink_three {
  margin-top: 2rem;
  width: 80%;
  padding: 2.5rem 1.5rem 2.5rem 1.5rem;
  border-radius: 15px;
  color: white;
  background-color: rgb(234, 41, 99);
  // margin: 0 auto;
  font-family: one;
  font-size: 20px;
  border: 2px white solid;
}

.pink_three>h1 {
  font-family: three;
  font-size: 50px;
  line-height: 40px;
}

.pink_three>p {
  margin-top: 1rem;
  text-align: left;
  line-height: 30px;
}

.pink_four {
  width: 85%;
  margin: 2rem auto;
  display: flex;
  justify-content: space-between;
}

.pink_four_1 {
  width: 30%;
  // height: 20rem;
  border-radius: 15px;
  background-color: #DB67A0;
  border: 2px white solid;
}

.pink_four_1>h1 {
  padding-top: 1rem;
  font-family: three;
  color: white;
}

.pink_four_1>p {
  width: 90%;
  color: white;
  font-size: 15px;
  text-align: left;
  font-family: two;
  padding: 0 1.5rem 2rem 1.5rem;
}

.pink_four_2 {
  width: 30%;
  // height: 20rem;

  border-radius: 15px;
  background-color: rgb(46, 84, 135);
  border: 2px white solid;
}

.pink_four_2>h1 {
  padding-top: 1rem;
  font-family: three;
  color: white;
}

.pink_four_2>p {
  width: 90%;
  color: white;
  font-size: 15px;
  text-align: left;
  font-family: two;
  padding: 0 1.5rem 2rem 1.5rem;
}

.pink_four_3 {
  width: 30%;
  // height: 20rem;
  border-radius: 15px;
  background-color: rgb(6, 2, 245);
  border: 2px white solid;
}

.pink_four_3>h1 {
  font-size: 18px;
  padding-top: 1rem;
  font-family: three;
  color: white;
  margin-bottom: 1rem;
}

.pink_four_3>p {
  width: 90%;
  font-family: two;
  color: white;
  font-size: 12px;
  text-align: left;
  padding: 0 1.5rem 2rem 1.5rem;
}

.road {
  width: 100%;
  // height: 120rem;
  position: relative;
  margin-top: 10rem;
  padding-bottom: 10rem;
}

.road_one {
  width: 80%;
  margin: 0 auto;
  text-align: center;
  // margin-top: 10rem;
}

.road_one>h1 {
  font-family: three;
  font-size: 70px;
  line-height: 40px;
  color: white;
  text-shadow: 0px 0px 17px #FF009C;
}

.road_one>span {
  display: block;
  line-height: 40px;
  color: white;
  margin-top: 2rem;
  margin-bottom: 2rem;
  text-shadow: 0px 0px 17px #FF009C;
}

.road_ones {
  width: 70%;
  margin: 0 auto;
  display: flex;
  font-family: four;
  justify-content: space-around;
  padding-bottom: 10rem;
}

.road_two {
  width: 28%;
  border: 2px white solid;
  color: white;
  background-color: rgb(219, 103, 160);
  padding-top: 4rem;

  padding-bottom: 5rem;
  border-radius: 15px;
}

.road_two>h1 {
  font-family: three;
  padding-left: 1rem;
  margin-bottom: 1rem;
}

.road_two>li {
  font-size: 12px;
  line-height: 20px;
  padding-left: 2rem;
}

.road_three {
  width: 28%;
  border: 2px white solid;
  color: white;
  background-color: #2E5487;
  padding-top: 4rem;

  padding-bottom: 5rem;
  border-radius: 15px;
}

.road_three>h1 {
  font-family: three;
  padding-left: 1rem;
  margin-bottom: 1rem;
}

.road_three>li {
  font-size: 12px;
  line-height: 20px;
  padding-left: 2rem;
}

.road_four {
  width: 28%;
  border: 2px white solid;
  color: white;
  background-color: rgb(6, 2, 245);
  padding-top: 4rem;

  padding-bottom: 5rem;
  border-radius: 15px;
}

.road_four>h1 {
  font-family: three;
  padding-left: 1rem;
  margin-bottom: 1rem;
}

.road_four>li {
  font-size: 12px;
  line-height: 20px;
  padding-left: 2rem;
}

.xm_ann {
  width: 80%;
  margin: 0 auto;
  display: flex;
  padding-top: 20rem;
  position: relative;
  top: 1%;
}

.xm_aone {
  width: 50%;
  justify-content: center;
  display: flex;
  align-items: center
}

.xm_atwo {
  width: 30rem;
  height: 24rem;
  border: 2px white solid;
  background-color: rgb(219, 103, 160);
  display: flex;
  flex-direction: column;
  justify-content: center;
  border-radius: 15px;
  padding-left: 2rem;
}

.xm_atwo>h1 {
  font-family: three;
  color: white;
  font-size: 40px;
}

.xm_atwo>p {
  font-size: 13px;
  font-family: four;
  color: white;
  margin-bottom: 2rem;
}

.xm_atwo>div {
  width: 10rem;
  height: 3rem;
  border-radius: 10px;
  line-height: 3rem;
  text-align: center;
  border: 1px white solid;
  background-color: rgb(234, 41, 99);
}

.xm_atwo>div>a {
  color: white;
}

.xm_ann>img {
  width: 500px;
  height: 500px;
}

.xm_three {
  width: 50%;
  display: flex;
  justify-content: center
}

.clog {
  width: 100%;
  // height: 60rem;
  background-color: white;
}

.clog>h1 {
  padding-top: 8rem;
  text-align: center;
  font-family: three;
  color: rgb(234, 41, 99);
  font-size: 75px;
}

.clong {
  width: 60%;
  border: 1px white solid;
  margin: 0 auto;
}

.cong_1 {
  width: 100%;
  position: relative;
  top: 1%;
}

.clong_one {
  width: 100%;
  color: white;
  padding: 1.2rem 0 1.2rem 1rem;
  background-color: rgb(234, 41, 99);
  border: 1px white solid;
}

.clong_two {
  width: 100%;
  background-color: rgb(242, 131, 150);
  color: white;
  line-height: 30px;
  padding: 1.2rem 0 1.2rem 1rem;
}

.button {
  width: 60%;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.button h1 {
  text-align: center;
  color: rgb(234, 41, 99);
  font-family: three;
  font-size: 60px;
  line-height: 55px;
}

.button>p {
  max-width: 860px;
  width: 82%;
  margin: 1rem 0 1rem 0;
  font-size: 14px;
  color: rgb(242, 131, 150);
  text-align: center;
}

.but_2 {
  // width: 80%;
  display: flex;
  margin: 2rem 0 1rem 0;
}

.but_2>a {
  margin-left: 1rem;
}

.but_2>a>img {
  width: 40px;
  height: 40px;
}

.but_one {
  display: flex;
  align-items: center;
}

.but_o1 {
  width: 240px;
  height: 153px;
}

.but_o2 {
  width: 285px;
  height: 85px;
}

.but_two {
  color: rgb(242, 131, 150);
  text-align: center;
  font-family: four;
}

@media (max-width: 600px) {
  .head_one {
    display: none;
  }

  .head {
    justify-content: center;
  }

  .cen_img {
    width: 350px;
    height: 350px;
  }

  .cen_1 {
    width: 100%;
  }

  .cen_2 {
    width: 95%;
    flex-wrap: wrap;
    justify-content: center;
  }

  .cen_2>a>img {
    width: 50px;
    height: 50px;
  }

  .cen_3 {
    width: 85%;
    font-size: 12px;
  }

  .cen_4 {
    width: 99%;
  }

  .cen_4>h1 {
    font-size: 60px;
  }

  .cen_5 {
    justify-content: space-around;
    flex-direction: column;
  }

  .cen_5>div {
    width: 98%;
  }

  .cen_6 {
    justify-content: space-around;
    flex-direction: column;
  }

  .cen_6>div {
    width: 98%;
    align-items: center;
    justify-content: center;
  }

  .cen_tp6 {
    margin-bottom: 2rem;
  }

  .wave-div {
    width: 100%;
    height: 12rem;
    background-image: url("http://localhost:8080/img/img1.70baa066.png");
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: relative;
    top: -5%;
  }

  .xmd_one {
    width: 100%;
    flex-direction: column;
  }

  .xmd_two>img:nth-child(1) {
    width: 350px;
    height: 350px;
  }

  .head>img {
    margin-left: 0;
  }

  .xmo {
    height: 120rem;
  }

  .xmd_two {
    width: 100%;
  }

  .xmd_thre {
    width: 100%;
  }

  .xmd_thre>img {
    width: 290px;
    height: 79px;
  }

  .wave-divs {
    width: 100%;
    height: 12rem;
    background-image: url(http://localhost:8080/img/img1.70baa066.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: relative;
    top: 10%;
  }

  .pink_one {
    width: 100%;
  }

  .pink_two>p {
    width: 90%;
    font-size: 12px;
  }

  .pink_four {
    width: 90%;
    flex-direction: column;
    align-items: center;
  }

  .pink_four>div {
    margin-bottom: 2rem;
  }

  .pink_ones {
    width: 90%;
  }

  .pink_ones>h1 {
    font-size: 55px;
  }

  .pink_four_1 {
    width: 21rem;
  }

  .pink_four_2 {
    width: 21rem;
  }

  .pink_four_3 {
    width: 21rem;
  }

  .wave-divsx {
    height: 12rem;
    top: -9%;
  }

  .road_ones {
    width: 85%;
    flex-direction: column;
  }

  .road_ones>div {
    margin-bottom: 2rem;
  }

  .road_two {
    width: 100%;
  }

  .road_three {
    width: 100%;
  }

  .road_four {
    width: 100%;
  }

  .wave-divsd {
    height: 12rem;
    top: 57%;
  }

  .xm_ann {
    flex-direction: column;
    align-items: center;
  }

  .xm_aone {
    width: 100%;
    margin-bottom: 2rem;
  }

  .xm_three {
    width: 100%;
  }

  .xm_three>img {
    width: 350px;
    height: 350px;
  }

  .wave-divsds {
    width: 100%;
    height: 13rem;
    background-image: url(http://localhost:8080/img/img1.70baa066.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: absolute;
    top: 96%;
  }

  .clong {
    width: 80%;
  }

  .wave-divsdsb {
    width: 100%;
    height: 12rem;
    background-image: url(http://localhost:8080/img/img1.70baa066.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: relative;
    top: 3%;
  }

  .button {
    width: 85%;
  }

  .but_2 {
    width: 80%;
    flex-wrap: wrap;
    justify-content: center;
  }

  .but_o1 {
    width: 80px;
    height: 55px;
  }

  .but_o2 {
    width: 102px;
    height: 35px;
  }

  .wave-divsboxd {
    height: 12rem;
  }
}</style>
