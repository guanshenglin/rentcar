<template>
  <div class="chong_fourthly">
    <Chongz>
      <p slot="text">充值</p>
    </Chongz>
    <div class="conent">
      <img src="./../assets/img/recharge/支付成功插画@2x.png" alt />
      <p>充值金额</p>
      <p>1000</p>
      <ul>
        <li>支付方式</li>
        <li><span>微信支付</span>  
          <span class="map">
           <img src="./../assets/img/recharge/icon-07@2x.png" alt="">
           <img src="./../assets/img/recharge/icon-9-png@2x.png" alt="">
          </span>
          </li>
         <li><span>支付宝支付</span>  
          <span class="map">
           <img src="./../assets/img/recharge/icon-06@2x.png" alt="">
           <img src="./../assets/img/recharge/icon-9-png@2x.png" alt="">
          </span>
          </li>
           <li><span>银联云闪付</span>  
          <span class="map">
           <img src="./../assets/img/recharge/icon-08@2x.png" alt="">
           <img src="./../assets/img/recharge/icon-9-png@2x.png" alt="">
          </span>
          </li>
      </ul>
      <div>
        <input type="radio" radio />同意平驾分时租车租赁协议
      </div>
          <p class="pay"><button>支付</button></p>
    </div>
  </div>
</template>

<script>
import Chongz from "./../components/chongz";
export default {
  data() {
    return {};
  },
  methods: {},
  components: {
    Chongz
  }
};
</script>

<style scoped lang='less'>
.chong_fourthly {
  height: 100%;
  background: #fafafa;
  .conent {
    margin: 0.32rem auto;
    width: 6.86rem;
    border-radius: 20px;
    background: #ffffff;
    img {
      width: 3.27rem;
      height: 2.96rem;
      margin: 0.3rem 0rem 0.24rem 2rem;
    }
    p {
      font-size: 0.24rem;
      font-weight: 600;
      text-align: center;
    }
    p:nth-child(3) {
      font-size: 0.72rem;
    }
    ul {
      li {
        display: flex;
        span{
            height: .44rem;
            line-height: .44rem;
           flex: 4;
        }
        .map{
          flex: 1;
          img{
          margin: 0;
          width: .44rem;
          height: .44rem;
          }
        }
        padding: 0.31rem 0rem 0.31rem 0.32rem;
        font-size: 0.28rem;
        border-bottom: 1px solid #e8e8e8;
      }
    }
    div{
      text-align: center;
      font-size: .24rem;
      padding: .31rem 0rem 0rem 0rem;
    }
    .pay{
      padding: .23rem .32rem .31rem .32rem;
      button {
      width: 6.21rem;
      height: 0.88rem;
      font-size: 0.36rem;
      font-weight: 500;
      border-radius: 28px;
      border: none;
      outline: none;
      text-align: center;
      background: linear-gradient(
        90deg,
        rgba(251, 236, 129, 1),
        rgba(255, 224, 9, 1)
      );
    }
    }
  }
}
</style>
