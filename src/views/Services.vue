<template>
  <div class="">
    <section class="h-[300px] md:h-[556px] bg-service bg-cover bg-center">
      <div class="container flex justify-center items-center px-4 h-full">
        <div class="z-10 break-words" data-aos="zoom-in" data-aos-delay="800">
          <div class="smAreaC z-16">
            <div class="h-[35px] w-[280px] md:w-[360px] z-20 mx-auto">
              <div class="overflow-hidden z-16">
                <div class="h-full z-16">
                  <div class="h-full break-words editableContent z-16">
                    <p class="w-full text-center z-16">
                      <span class="text-white z-16"
                        ><strong class="z-16"
                          ><span class="text-[24px] md:text-[34px] z-16"
                            ><span class="font-['Source_Han_Sans'] z-16"
                              >Baoboサービス</span
                            ></span
                          ></strong
                        ></span
                      >
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <br />
            <div class="esmartMargin smartAbs h-[35px] w-full z-21">
              <div
                class="overflow-hidden yibuFrameContent con_12_32 text_Style1 z-16"
              >
                <div class="h-full z-16">
                  <div class="h-full break-words editableContent z-16">
                    <p class="text-center z-16">
                      <span class="tracking-[4px] z-16"
                        ><span class="text-[#33ffcc] z-16"
                          ><span class="font-['Arial_Black'] z-16"
                            ><span class="text-xs md:text-sm z-16"
                              >B</span
                            ></span
                          ></span
                        ><span class="text-white font-['Arial_Black'] z-16"
                          ><span class="text-xs md:text-sm z-16"
                            >AOBO
                          </span></span
                        ><span class="text-[#33ffcc] z-16"
                          ><span class="font-['Arial_Black'] z-16"
                            ><span class="text-xs md:text-sm z-16"
                              >S</span
                            ></span
                          ></span
                        ><span class="text-white font-['Arial_Black'] z-16"
                          ><span class="text-xs md:text-sm z-16"
                            >ERVICES</span
                          ></span
                        ></span
                      >
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="py-8 bg-gray-50 section md:py-16">
      <div class="container px-2 md:px-4">
        <div
          class="flex justify-center mx-auto mb-14 h-[79px] w-[280px] md:w-[360px] z-2"
        >
          <div class="overflow-hidden yibuFrameContent con_95_41 text_Style1">
            <div id="txt_con_95_41" class="h-full">
              <div
                class="h-full break-words editableContent"
                id="txtc_con_95_41"
              >
                <p class="text-center">
                  <span class="leading-[1.5]"
                    ><span class="text-[28px] md:text-[36px]"
                      ><span class="font-['Source_Han_Sans']"
                        ><strong
                          ><span class="text-black"
                            >サービス</span
                          ></strong
                        ></span
                      ></span
                    ></span
                  >
                </p>

                <p class="text-center">
                  <span class="text-base"
                    ><span class="font-['Trebuchet_MS']"
                      ><span class="text-gray-500"
                        ><span class="leading-[1.5]">OUR SERVICE</span></span
                      ></span
                    ></span
                  >
                </p>
              </div>
            </div>
          </div>
        </div>

        <div class="container px-2 md:px-4">
          <div class="flex flex-wrap gap-y-8 justify-evenly md:gap-y-14">
            <div
              class="flex w-full md:flex-row item md:w-auto"
              v-for="value in serviceItems"
            >
              <div
                class="icon w-[35px] h-[35px] md:w-[45px] md:h-[45px] bg-cover bg-center mb-2 md:mb-0 mx-auto md:mx-0"
                :class="value.class"
              ></div>
              <div
                style="
                  /* height: 81px; */
                  width: 285px;
                  left: 55px;
                  top: 0px;
                  z-index: 3;
                "
              >
                <div
                  class="overflow-hidden yibuFrameContent con_82_41 text_Style1"
                >
                  <div id="txt_con_82_41" class="h-full">
                    <div
                      class="h-full break-words editableContent"
                      id="txtc_con_82_41"
                    >
                      <p>
                        <span class="font-['Microsoft_YaHei']"
                          ><span class="text-lg md:text-xl">{{
                            value.title
                          }}</span></span
                        >
                      </p>

                      <p>
                        <span class="text-xs md:text-sm"
                          ><span class="text-gray-500"
                            ><span class="leading-[1.75]">{{
                              value.description
                            }}</span></span
                          ></span
                        >
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section
      class="bg-service_bg2 h-auto md:h-[554px] bg-cover bg-center pb-8 md:pb-0 bg-scroll"
    >
      <div class="container mx-auto">
        <div class="py-12 mx-auto w-max md:py-20">
          <div class="smAreaC" cid="con_71_49">
            <div class="h-[42px] w-[320px] md:w-[431px] z-2 mx-auto">
              <div
                class="overflow-hidden yibuFrameContent con_72_49 text_Style1"
              >
                <div class="h-full">
                  <div class="h-full break-words editableContent">
                    <p class="text-center">
                      <span class="text-[28px] md:text-[40px]"
                        ><span class="font-['Arial']"
                          ><strong
                            ><span class="text-white"
                              >OUR ADVANTAGE</span
                            ></strong
                          ></span
                        ></span
                      >
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="h-[30px] min-w-[140px] z-9 mx-auto mt-4">
              <div
                class="overflow-hidden yibuFrameContent con_73_49 text_Style1"
              >
                <div class="h-full">
                  <div class="h-full break-words editableContent">
                    <p class="text-center">
                      <span class="text-lg md:text-2xl"
                        ><span class="text-white">私たちの強み（Our Strengths）</span></span
                      >
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="h-[20px] w-[85px] z-8 mx-auto mt-2">
              <div
                class="overflow-visible yibuFrameContent con_74_49 line_Style1"
              >
                <!-- w-line -->
                <div class="relative h-full">
                  <div class="w-line absolute top-1/2 w-[85px]"></div>
                </div>
              </div>
            </div>
            <div class="h-[20px] w-[83px] z-8 mx-auto mt-2">
              <div
                class="overflow-visible yibuFrameContent con_75_49 line_Style1"
              >
                <!-- w-line -->
                <div class="relative h-full">
                  <div
                    class="w-line absolute top-1/2 w-[83px]"
                    linetype="horizontal"
                  ></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="flex flex-wrap gap-8 justify-evenly px-4 md:gap-0 service-wrap"
        >
          <div
            class="flex flex-col justify-center items-center w-full service-item sm:w-1/2 md:w-auto"
            :data-aos="value.aos"
            :data-aos-delay="value.aosDelay"
            v-for="value in advantage"
          >
            <div
              class="icon border-[1px] border-solid border-[#666] rounded-full w-[70px] h-[70px] md:w-[98px] md:h-[98px] flex justify-center items-center mb-4"
            >
              <img
                :src="value.class"
                alt=""
                class="w-[35px] h-[35px] md:w-[50px] md:h-[50px]"
              />
            </div>
            <div
              style="
                height: 49px;
                width: 160px;
                left: 30px;
                top: 168px;
                z-index: 6;
              "
            >
              <div
                class="overflow-hidden yibuFrameContent con_59_49 text_Style1"
              >
                <div id="txt_con_59_49" class="h-full">
                  <div
                    class="h-full break-words editableContent"
                    id="txtc_con_59_49"
                  >
                    <p class="text-center">
                      <span class="text-3xl md:text-5xl"
                        ><span class="text-white"
                          ><span class="font-['Arial_Black']">{{
                            value.title
                          }}</span></span
                        ></span
                      >
                    </p>
                  </div>
                </div>
              </div>
            </div>

            <div class="overflow-hidden yibuFrameContent con_60_49 text_Style1">
              <div id="txt_con_60_49" class="h-full">
                <div class="h-full break-words editableContent">
                  <p class="text-center">
                    <span class="text-sm md:text-base"
                      ><span class="text-white font-['Arial']">{{
                        value.desc
                      }}</span></span
                    >
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import service1 from '@/assets/images/service/1.svg'
import service2 from '@/assets/images/service/2.svg'
import service3 from '@/assets/images/service/3.svg'
import service4 from '@/assets/images/service/4.svg'

export default {
  name: 'service',
  setup() {
    const serviceItems = [
      {
        class: 'bg-service1',
        title: 'カスタマイズソリューション',
        description:
          'エンジニアリング・電気機械・ネットワークの各専門チームが、運用保守チームと緊密に連携し、お客様の実際のニーズに合わせた柔軟なサービス設計・提供を行います。',
      },
      {
        class: 'bg-service2',
        title: '多言語サポート',
        description: '中国語・英語・韓国語・日本語による多言語オンライン技術サポートを提供し、グローバルなお客様を包括的にサポートします。',
      },
      {
        class: 'bg-service3',
        title: 'ネットワーク監視・運用管理',
        description:
          '24時間365日のネットワーク監視体制を整え、リアルタイムで障害検知・統計・技術支援を行い、安定したネットワーク運用を確保します。',
      },
      {
        class: 'bg-service4',
        title: '物流・倉庫サービス',
        description:
          '一般貨物から高価値機器まで、安全かつ効率的な輸送と通関をサポート。複数地域に信頼性の高い倉庫スペースを確保し、柔軟なストレージ・ロジスティクスを実現します。',
      },
      {
        class: 'bg-service5',
        title: 'IDCオンサイトサービス',
        description:
          'お客様からの委託に基づき、Remote Hands・Smart Hands サービスを提供。機器設置、交換、ケーブリングなどの作業を迅速かつ正確に実施します。',
      },
      {
        class: 'bg-service6',
        title: '迅速な対応体制',
        description: '専門チームが24時間待機し、5分以内の応答、2時間以内に都市圏のあらゆるIDCへ駆け付け可能な体制を整えています。',
      },
    ]

    const advantage = [
      {
        class: service1,
        title: '12+',
        aos: 'fade-left',
        aosDelay: 600,
        desc: '年年間業界での経験',
      },
      {
        class: service2,
        title: '100%',
        aos: 'fade-left',
        aosDelay: 300,
        desc: '顧客満足度',
      },
      {
        class: service3,
        title: '100+',
        aos: 'fade-right',
        aosDelay: 300,
        desc: 'パートナーシップの構築',
      },
      {
        class: service4,
        title: '25+',
        aos: 'fade-right',
        aosDelay: 600,
        desc: '都市拠点サービスチーム',
      },
    ]
    return { serviceItems, advantage }
  },
}
</script>

<style></style>
