<template>
  <div>
    <section class="h-[300px] md:h-[500px] bg-product bg-cover bg-center">
      <div class="container flex justify-center items-center px-4 h-full">
        <div class="z-10 break-words" data-aos="zoom-in" data-aos-delay="800">
          <p class="z-10 text-center">
            <span
              class="text-white font-['Source_Han_Sans',Geneva,sans-serif] z-10"
            >
              <span class="text-[24px] md:text-[34px] z-10">製品紹介</span>
            </span>
          </p>

          <p class="z-10 mt-2 text-center">
            <span class="font-['Arial_Black'] z-10">
              <span class="z-10 text-white">
                <span class="z-10 text-xs md:text-sm"
                  >Product Introduction</span
                >
              </span>
            </span>
          </p>
        </div>
      </div>
    </section>

    <section class="bg-[#f3f4f5] section py-8 md:py-16">
      <div class="container px-2 md:px-4 mx-auto md:h-[650px] h-max">
        <swiper
          :spaceBetween="30"
          :effect="'fade'"
          :autoplay="{
            delay: 3000,
            disableOnInteraction: false,
          }"
          :pagination="{
            clickable: true,
          }"
          :modules="modules"
          class="mySwiper"
        >
          <swiper-slide class="">
            <div class="pl-4 h-full bg-white md:pl-10 wrap">
              <div
                class="flex pb-10 h-full max-md:flex-col md:justify-between content"
              >
                <div class="p-4 md:p-[50px]">
                  <div class="overflow-hidden z-10">
                    <div class="z-10 h-full">
                      <div class="z-10 h-full break-words">
                        <h2 class="z-10 mb-2 md:mb-4">
                          <span class="font-['Source_Han_Sans'] z-10"
                            ><span class="text-[18px] md:text-[24px] z-10"
                              ><strong class="z-10"
                                >企業ネットワークサービス</strong
                              >
                            </span>
                          </span>
                        </h2>

                        <p style="z-index: 1">
                          <span style="font-size: 14px; z-index: 1"
                            ><strong style="z-index: 1"
                              >Enterprise Network Services</strong
                            >
                          </span>
                        </p>

                        <p class="z-10 mb-3 md:mb-4">
                          <span
                            class="leading-[1.4] md:leading-[1.2] z-10 block"
                            ><strong class="z-10"
                              ><span class="text-[12px] md:text-[10.5pt] z-10"
                                ><span class="z-10 font-sans"
                                  >当社の光ファイバー基幹ネットワークおよびネットワークソリューションは、アジア太平洋地域をはじめ、世界の主要市場におけるレイテンシーと回復能力の向上を目的としています。
                                  お客様のあらゆるネットワークおよびインフラニーズに対応するために、きわめてパーソナライズされたワンストップソリューションを提供しています。</span
                                >
                              </span>
                            </strong>
                          </span>
                        </p>

                        <p class="z-10">
                          <span class="leading-[1.2] z-10 block"
                            ><strong class="z-10"
                              ><span class="text-[10.5pt] z-10"
                                ><span class="block z-10 font-sans"
                                  >Our fiber optic backbone and network
                                  solutions aim to improve latency/recovery
                                  capabilities in key markets in the Asia
                                  Pacific region and even globally. We provide
                                  highly personalized one-stop solutions to meet
                                  all your network and infrastructure
                                  needs.</span
                                >
                              </span>
                            </strong>
                          </span>
                        </p>

                        <p class="z-10 text-left">
                          <span class="leading-[1.2] z-10 block"
                            ><span class="text-[10.5pt] font-semibold z-10"
                              ><span class="z-10"
                                >1<span class="z-10 text-sm"
                                  >. WDM（波長分割多重）</span
                                >
                              </span>
                            </span>
                          </span>
                        </p>

                        <p class="z-10 text-left">
                          <span class="leading-[1.2] z-10 block"
                            ><span class="text-[10.5pt] z-10"
                              ><span class="z-10">
                                光ファイバーのバックボーンネットワークに基づくWDMサービスです。<br />
                                このサービスにより、お客様のコアネットワークのカバレッジを拡大することが可能です。<br />
                                波長は 1Gbps、10Gbps、100Gbps
                                のオプションをご用意しています。</span
                              >
                            </span>
                          </span>
                        </p>

                        <br />
                        <p class="z-10 text-left">
                          <span class="leading-[1.2] z-10 block"
                            ><span class="z-10 text-sm"
                              ><span class="z-10 font-semibold"
                                >2. EPL（Ethernet Private Line）</span
                              >
                            </span>
                          </span>
                        </p>
                        <p class="z-10 text-left">
                          <span class="leading-[1.2] z-10 block"
                            ><span class="text-[10.5pt] z-10"
                              ><span class="z-10"
                                >専用で管理可能なポイント・ツー・ポイント型のレイヤー2
                                MPLSイーサネットサービスで、最大 10Gbps
                                の速度に対応します。<br />
                                各種MTUやVLANタグ設定をサポートしており、世界各国でのクロスボーダーおよびローカルループ接続を提供可能です。</span
                              >
                            </span>
                          </span>
                        </p>

                        <p class="z-10 text-left">&nbsp;</p>

                        <p class="z-10 text-left">
                          <span class="leading-[1.2] z-10 block"
                            ><span class="z-10 text-sm"
                              ><span class="z-10 font-semibold"
                                >3. WAVELIGHT & ダークファイバー</span
                              >
                            </span>
                          </span>
                        </p>

                        <p class="z-10 text-left">
                          <span class="leading-[1.2] z-10 block"
                            ><span class="text-[10.5pt] z-10"
                              ><span class="z-10"
                                >お客様は、必要な帯域容量に応じて当社のWDMネットワーク上で独自の多重化装置を使用することができます。<br />
                                また、当社が提供する多重化装置をレンタルすることも可能です。<br />
                                さらに、都市圏ネットワークにおいてダークファイバーサービスも提供しています。</span
                              >
                            </span>
                          </span>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="w-full md:w-[330px] flex-shrink-0 h-[200px] md:h-full bg-product1 bg-cover bg-center"
                ></div>
                <!-- <img src="@/assets/images/product/1.png" alt="" class="w-[330px] h-full" /> -->
              </div>
            </div>
          </swiper-slide>
          <swiper-slide class=""
            ><div class="pl-4 h-full bg-white md:pl-10 wrap">
              <div
                class="flex pb-10 h-full max-md:flex-col md:justify-between content"
              >
                <div class="p-4 md:p-[50px]">
                  <div class="overflow-hidden z-10">
                    <div class="z-10 h-full">
                      <div class="z-10 h-full break-words">
                        <h2 class="z-10 mb-2 md:mb-4">
                          <span class="font-['Source_Han_Sans'] z-10"
                            ><span class="text-[18px] md:text-[24px] z-10"
                              ><strong class="z-10"
                                >ビジネス向け高速・低遅延ネットワークソリューション</strong
                              ></span
                            ></span
                          >
                        </h2>

                        <p style="z-index: 6">
                          <span style="font-size: 14px; z-index: 6"
                            ><strong style="z-index: 6"
                              >High speed low latency commercial network</strong
                            ></span
                          >
                        </p>

                        <p class="z-10">
                          <span
                            class="leading-[1.6] md:leading-[1.5] z-10 block"
                            ><span class="text-[12px] md:text-sm z-10"
                              ><span class="z-10"
                                ><span class="z-10 font-sans">
                                  当社は自社でネットワークを保有・運営しており、比類のない速度、信頼性、性能、そしてサービスを実現するカスタマイズ型ソリューションをお客様に提供しています。
                                  帯域幅は1Mbpsから最大10Gbpsまでの高帯域サービスに対応し、最新のネットワーク技術を活用して、お客様のあらゆるニーズにお応えします。</span
                                ></span
                              ></span
                            ></span
                          >
                        </p>

                        <p class="z-10">
                          <span
                            class="leading-[1.6] md:leading-[1.5] z-10 block"
                            ><span class="text-[12px] md:text-sm z-10"
                              ><span class="z-10 font-sans"
                                >さらに、アジア太平洋市場への展開を支援する多くの機会を有しています。
                                褒博（バオボ）テクノロジーの開発チームの継続的な技術革新により、東京、シンガポール、香港、台北、上海、深センなど、各都市の金融取引所を結ぶトップクラスの回線リソースを確立しています。</span
                              ></span
                            ></span
                          >
                        </p>

                        <p class="z-10 md:mb-4">
                          <span
                            class="leading-[1.6] md:leading-[1.5] z-10 block"
                            ><span class="text-[12px] md:text-sm z-10"
                              ><span class="z-10"
                                >当社の専用線サービスは、帯域をエンドツーエンドで物理的に分離し、専用利用が可能な高可用ネットワークを提供します。
                                可用率は99.99%以上を保証し、ミリ秒単位の超低遅延を実現しています。</span
                              ></span
                            ></span
                          >
                        </p>

                        <p class="z-10">
                          <span class="leading-[1.5] z-10 block"
                            ><span class="z-10 text-sm"
                              ><span class="z-10 font-sans"
                                ><span class="block z-10 font-sans"
                                  >&nbsp; We own and operate our own network,
                                  and we can provide you with unparalleled
                                  customized solutions for speed, reliability,
                                  performance, and service. Our capacity options
                                  range from 1 Mbps to high bandwidth services
                                  up to 10 Gbps. We use the latest network
                                  technology to help our customers meet all
                                  their requirements.<br class="z-10" />
                                  &nbsp; We have more opportunities to help our
                                  clients expand into the Asia Pacific market.
                                  Based on the continuous progress of the
                                  BAOBO's&nbsp;development team, we have
                                  top-level route resources connecting various
                                  financial exchanges in cities such as Tokyo,
                                  Singapore, Hong Kong, Taipei, Shanghai, and
                                  Shenzhen.<br class="z-10" />
                                  Broadband end-to-end hard isolation, dedicated
                                  line, high availability, with an availability
                                  rate of no less than 99.99%, and millisecond
                                  level to ensure low latency.</span
                                ></span
                              ></span
                            ></span
                          >
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="w-full md:w-[330px] flex-shrink-0 h-[200px] md:h-full bg-product2 bg-cover bg-center"
                ></div>
              </div>
            </div>
          </swiper-slide>
        </swiper>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref, onMounted, computed } from 'vue'

import { Swiper, SwiperSlide } from 'swiper/vue'

import { EffectFade, Navigation, Pagination, Autoplay } from 'swiper/modules'
const modules = [EffectFade, Navigation, Pagination, Autoplay]
import 'swiper/css'
import 'swiper/css/effect-fade'
import 'swiper/css/navigation'
import 'swiper/css/pagination'
import 'swiper/css/autoplay'
</script>
<style scoped>
.mySwiper {
  @apply mx-auto;
  width: 100%;
  height: 100%;
}
.swiper {
  width: 100%;
  height: 100%;
}
@media (max-width: 768px) {
  .mySwiper {
    width: 100%;
    height: auto;
    min-height: 400px;
  }
}
</style>
