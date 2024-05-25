<template>
    <div class="q-pa-md">
      <div class="grid-wrapper q-gutter-md">
        <q-card v-for="(card, index) in cards" :key="index" class="my-card">
          <img :src="card.img" class="card-img">
          <q-card-section>
            <div class="text-h6">{{ card.title }}</div>
            <div class="text-subtitle2">{{ card.harga }}</div>
          </q-card-section>
          <q-card-section class="q-pt-none">
            {{ card.description }}
          </q-card-section>
        </q-card>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    setup() {
      return {
        cards: [
          {
            img: "https://images.tokopedia.net/img/cache/500-square/VqbcmM/2024/1/3/6c5e615d-2ce2-404e-84c8-af0ea5ce7a8b.jpg",
            title: "Dior",
            harga: "Rp 1.700.000",
            description: "Sepatu Sneaker Pria DY322"
          },
          {
            img: "https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//109/MTA-91987183/no_brand_sepatu_new_balance_574_ml574lgi_beige_navy_full04_lulpbk7u.jpg",
            title: "New Balance",
            harga: "Rp 1.200.000",
            description: "SEPATU NEW BALANCE 574 ML574LGI BEIGE NAVY"
          },
          {
            img: "https://img.ws.mms.shopee.co.id/b74a96fb5c0ac1fd9c0f9f54f5165021",
            title: "Rebook",
            harga: "Rp 450.000",
            description: "Sepatu Clasic Utility Rebook Brown"
          },
          {
            img: "https://cf.shopee.co.id/file/id-11134207-7r98o-lnl3nhkixsqib2",
            title: "Hermes",
            harga: "Rp 1.850.000",
            description: "Hermes Mirror Branded"
          },
          {
            img: "https://img.ws.mms.shopee.co.id/sg-11134201-22110-fpw1cuyw2ojvdd",
            title: "Louis Vuitton",
            harga: "Rp 2.100.000",
            description: "Sneaker Lv Hitam Hitam Cowok Run Away Men Shoes Mirror Vip Sepatu Pria p1shoes"
          },
          {
            img: "https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcS1r7BtEOHt61AHyersVfjpCfNUmFAMtdCFVt27GGvA71Msu65EH4yBs9ScerT4g8vIi4U3b5bNGCVHaJCupISk_Fxehyi9sFOP0K_nV-vdOMVLFopdjOgLFw&usqp=CAE",
            title: "Fitflop",
            harga: "Rp 999.000",
            description: "Sandal Pria Fitflop Surfer Woven-Logo Navy Ez8-399 - 40"
          },
          {
            img: "https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcR2MDDc9KC6NJpMmENiX9Ftgp6k9zmO8iH4c8EhaF-W-MLCmXqbn3qectzKCp07UeU-JngG05rg7WGvcdfNCxuBQ31a97pIygP7z12i9F_7VF93bLB5Lcwg&usqp=CAE",
            title: "Quick Silver",
            harga: "Rp 899.000",
            description: "Sandal Pria Slide Quiksilver Original Mathodic Riecovery Kvj1 New"
          },
          {
            img: "https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcSK8jSbwJDye7JfZvcPZhktw7qNXI_NUrypcHcnYoM4rY9MeQwG4l_dRJgvt-_bsMqZmHDuIcIJBmxpZ4po35kwsp55wP8istAVtrwfOILS8Pq12oJVN_gxdA&usqp=CAE",
            title: "Nike",
            harga: "Rp 200.000",
            description: "Nike Calm Mens"
          },
          {
            img: "https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcSlk8gdHsPZzaARwTjzmAX7wl8-RovnjIs-MiAS9Nf4ldHbjA772a90F8aXRhtaL8l9JmhaHm-uYLd0Gyg8E5Fm9FE23qdqnTVpSRD0tJvu&usqp=CAE",
            title: "GMX",
            harga: "Rp 220.000",
            description: "Geoff Max Star War"
          },
          {
            img: "https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcQt8058cfSIUBTVSg2C2pIJjMDiSZz2_ugzl5-KsSwrgGqxy1CjWp_kT-v01f5MLSF2byvXvLOKvUvgHTEMI4gSfvcAOOxhZgB-ZupenRMK1WerqjzsN0Q6dg&usqp=CAE",
            title: "Prada",
            harga: "Rp 14.220.000",
            description: "Prada Logo Plaque Leather SlidesHighlightsSandals with triangle"
          },
          {
            img: "https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcQqLMLxediRWjLOZGzBA7za1RJvr4nZm4_TIsJgniafXOksABC9hVOmo2tIugjbaHTRT_gVYiRMlvauBErvwXhwgiffCysxrbm95GEg-zATSSQ25H89FQBGAQ&usqp=CAE",
            title: "Adidas",
            harga: "Rp 250.000",
            description: "Kaos Kaki"
          },
          {
            img: "https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcRq-5I3EUQ5vzrHh2xQAlzu2fvhRKFsK6sICrBXySGJC3ejrimkgCCXUT_wQQF2Z2ErhUIfK8_Upyt3phXq_j6PRBr2aSAVRUdSiz2Plm-_60tSweD98cX1Dg&usqp=CAE",
            title: "Jordan",
            harga: "Rp 269.000",
            description: "Kaos Kaki"
          },
          {
            img: "https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcR6eHbUuEa5ZjnjDiFwNeL4_vVdX_5zQg8Z8d68cePChQh9dbRuWS-eHEmJSHXvhcFgO1GXkn8HfjdpSRLlf9eNUZgEWX-KVfEp6Adyey2iMDvrMa-NnfN7vA&usqp=CAE",
            title: "Adidas",
            harga: "Rp 180.000",
            description: "Kaos Kaki"
          },
          {
            img: "https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcRtVMSp7I0I2-IRXQzemH9jSAZBEdrAAmHPoC7QtJ4i-GM-5hWgM2Wpc_fHV2kpTUs0gxjn_k06riahSxMbXzbk-EZkM6j6rF-8IskGOB6cIDkpFODMGNNY&usqp=CAE",
            title: "New Balance",
            harga: "Rp 129.000",
            description: "Kaos Kaki"
          },
          {
            img: "https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcQu9POk_5BAKemWA3XAmBkZOEAYcaqbVY5D105HPMV9cg_sUEUykAa1HFJ2G-_eD9gytbW87gIc2mmey2FOzpRz0HigxQRSfWe6crseapv5Ht662jmcihrtfQ&usqp=CAE",
            title: "Adidas",
            harga: "Rp 90.000",
            description: "Kaos Kaki"
          }
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  .grid-wrapper {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 16px;
  }
  
  .my-card {
    width: 100%;
    max-width: 100%;
    background-image: linear-gradient(45deg, #ffffff 0%, #c0c0c0 100%);
    border-radius: 5px;
    transition: all .3s;
    cursor: pointer;
  }
  
  .card-img {
    width: 100%;
    height: auto;
  }
  
  .my-card:hover {
    transform: scale(0.98);
  }
  
  @media (max-width: 600px) {
    .grid-wrapper {
      grid-template-columns: 1fr;
    }
  
    .my-card {
      margin-bottom: 16px;
    }
  }
  </style>
  