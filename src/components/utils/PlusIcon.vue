<template>
    <div>
        <div class="action-btn-main">
                <a href="#" class="icon" data-toggle="dropdown" aria-expanded="false">
                  <svg width="38" height="38" viewBox="0 0 38 38" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M1.21655 19.0676C1.21655 5.68036 5.68024 1.21667 19.0674 1.21667C32.4546 1.21667 36.9183 5.68036 36.9183 19.0676C36.9183 32.4547 32.4546 36.9184 19.0674 36.9184C5.68024 36.9184 1.21655 32.4547 1.21655 19.0676Z"
                      fill="#262626" stroke="#262626" stroke-linecap="round" stroke-linejoin="round"></path>
                    <path d="M19.0674 12.5148V25.6202" stroke="white" stroke-width="2" stroke-linecap="round"
                      stroke-linejoin="round"></path>
                    <path d="M25.6268 19.0675H12.5078" stroke="white" stroke-width="2" stroke-linecap="round"
                      stroke-linejoin="round"></path>
                  </svg>
                </a>
                <div class="dropdown-menu dropdown-menu-right control" style="">
                  <div class="modal-control-01">
                    <div class="modal-content">
                      <!-- modal content start -->
                      <div class="mini-modal-style-01">
                        <ul class="list">
                          <li class="list-item">
                            <span class="icon">
                              <svg width="22" height="24" viewBox="0 0 22 24" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                  d="M6.20007 5.59999C6.20007 4.32695 6.70578 3.10605 7.60596 2.20588C8.50613 1.3057 9.72703 0.799988 11.0001 0.799988C12.2731 0.799988 13.494 1.3057 14.3942 2.20588C15.2944 3.10605 15.8001 4.32695 15.8001 5.59999M11.0001 11.2V19.2M7.00007 15.2H15.0001M2.84167 10.224L1.59687 21.424C1.57212 21.6476 1.59481 21.8739 1.66345 22.0882C1.73209 22.3024 1.84514 22.4998 1.99522 22.6674C2.1453 22.835 2.32904 22.969 2.53444 23.0608C2.73985 23.1526 2.96229 23.2 3.18727 23.2H18.8129C19.0378 23.2 19.2603 23.1526 19.4657 23.0608C19.6711 22.969 19.8548 22.835 20.0049 22.6674C20.155 22.4998 20.268 22.3024 20.3367 22.0882C20.4053 21.8739 20.428 21.6476 20.4033 21.424L19.1585 10.224C19.1151 9.83249 18.9289 9.47073 18.6355 9.20798C18.342 8.94523 17.962 8.79996 17.5681 8.79999H4.43207C4.03818 8.79996 3.65812 8.94523 3.36467 9.20798C3.07121 9.47073 2.885 9.83249 2.84167 10.224Z"
                                  stroke="white" stroke-width="1.6"></path>
                              </svg>
                            </span>
                            <a href="/new_order" class="text">
                              Create Order
                            </a>
                          </li>
                          <li class="list-item" @click="addProdOnePopOpn">
                            <span class="icon">
                              <svg width="24" height="24" viewBox="0 0 24 24" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" clip-rule="evenodd"
                                  d="M16.436 1C20.063 1 22.5 3.546 22.5 7.335V16.165C22.5 19.954 20.063 22.5 16.436 22.5H7.064C3.437 22.5 1 19.954 1 16.165V7.335C1 3.546 3.437 1 7.064 1H16.436ZM16.436 2.5H7.064C4.292 2.5 2.5 4.397 2.5 7.335V16.165C2.5 19.103 4.292 21 7.064 21H16.436C19.209 21 21 19.103 21 16.165V7.335C21 4.397 19.209 2.5 16.436 2.5ZM7.1211 9.2025C7.5351 9.2025 7.8711 9.5385 7.8711 9.9525V16.8125C7.8711 17.2265 7.5351 17.5625 7.1211 17.5625C6.7071 17.5625 6.3711 17.2265 6.3711 16.8125V9.9525C6.3711 9.5385 6.7071 9.2025 7.1211 9.2025ZM11.7881 5.9185C12.2021 5.9185 12.5381 6.2545 12.5381 6.6685V16.8115C12.5381 17.2255 12.2021 17.5615 11.7881 17.5615C11.3741 17.5615 11.0381 17.2255 11.0381 16.8115V6.6685C11.0381 6.2545 11.3741 5.9185 11.7881 5.9185ZM16.3784 12.8275C16.7924 12.8275 17.1284 13.1635 17.1284 13.5775V16.8115C17.1284 17.2255 16.7924 17.5615 16.3784 17.5615C15.9644 17.5615 15.6284 17.2255 15.6284 16.8115V13.5775C15.6284 13.1635 15.9644 12.8275 16.3784 12.8275Z"
                                  fill="white"></path>
                              </svg>
                            </span>
                            <span class="text">
                              Add Product
                            </span>
                          </li>
                          <li class="list-item" @click="customerPopOpn">
                            <span class="icon">
                              <svg width="20" height="20" viewBox="0 0 20 20" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                  d="M11.2 11.8V15.4C11.2 15.5591 11.2632 15.7117 11.3757 15.8242C11.4882 15.9368 11.6408 16 11.8 16H15.4C15.5591 16 15.7117 15.9368 15.8242 15.8242C15.9367 15.7117 16 15.5591 16 15.4V11.8C16 11.6409 15.9367 11.4882 15.8242 11.3757C15.7117 11.2632 15.5591 11.2 15.4 11.2H11.8C11.6408 11.2 11.4882 11.2632 11.3757 11.3757C11.2632 11.4882 11.2 11.6409 11.2 11.8ZM12.4 14.8V12.4H14.8V14.8H12.4Z"
                                  fill="white"></path>
                                <path
                                  d="M3.9999 0.399994C3.91196 0.400027 3.8251 0.419392 3.74547 0.456719C3.66584 0.494045 3.59539 0.54842 3.5391 0.615994L0.539102 4.21599C0.449221 4.32378 0.399965 4.45965 0.399902 4.59999V6.39999C0.399902 7.46559 0.863102 8.42439 1.5999 9.08319V19C1.5999 19.1591 1.66312 19.3117 1.77564 19.4243C1.88816 19.5368 2.04077 19.6 2.1999 19.6H17.7999C17.959 19.6 18.1116 19.5368 18.2242 19.4243C18.3367 19.3117 18.3999 19.1591 18.3999 19V9.08319C19.1367 8.42319 19.5999 7.46559 19.5999 6.39999V4.59999V4.57839C19.5999 4.47039 19.5999 4.38399 19.4607 4.21599L16.4607 0.615994C16.4044 0.54842 16.334 0.494045 16.2543 0.456719C16.1747 0.419392 16.0878 0.400027 15.9999 0.399994H3.9999ZM3.9999 8.79999C3.36338 8.79999 2.75293 8.54714 2.30285 8.09705C1.85276 7.64696 1.5999 7.03651 1.5999 6.39999V5.19999H6.3999V6.39999C6.3999 7.03651 6.14705 7.64696 5.69696 8.09705C5.24687 8.54714 4.63642 8.79999 3.9999 8.79999ZM9.9999 8.79999C9.36338 8.79999 8.75293 8.54714 8.30285 8.09705C7.85276 7.64696 7.5999 7.03651 7.5999 6.39999V5.19999H12.3999V6.39999C12.3999 7.03651 12.147 7.64696 11.697 8.09705C11.2469 8.54714 10.6364 8.79999 9.9999 8.79999ZM15.9999 8.79999C15.3634 8.79999 14.7529 8.54714 14.3028 8.09705C13.8528 7.64696 13.5999 7.03651 13.5999 6.39999V5.19999H18.3999V6.39999C18.3999 7.03651 18.147 7.64696 17.697 8.09705C17.2469 8.54714 16.6364 8.79999 15.9999 8.79999ZM3.9999 18.4H2.7999V9.79599C3.55626 10.0641 4.38056 10.0715 5.14163 9.81711C5.9027 9.56269 6.55682 9.06105 6.9999 8.39199C7.32829 8.88691 7.77414 9.29278 8.29763 9.57337C8.82112 9.85396 9.40595 10.0005 9.9999 9.99999C10.594 10.0004 11.1789 9.85365 11.7024 9.57284C12.2259 9.29204 12.6717 8.88593 12.9999 8.39079C13.443 9.05985 14.0971 9.56149 14.8582 9.81591C15.6192 10.0703 16.4435 10.0629 17.1999 9.7948V18.4H9.9999V11.8C9.9999 11.6409 9.93669 11.4883 9.82417 11.3757C9.71165 11.2632 9.55903 11.2 9.3999 11.2H4.5999C4.44077 11.2 4.28816 11.2632 4.17564 11.3757C4.06312 11.4883 3.9999 11.6409 3.9999 11.8V18.4ZM6.5679 3.99999H2.2815L4.2807 1.59999H7.3671L6.5679 3.99999ZM12.1671 3.99999H7.8327L8.6319 1.59999H11.3679L12.1671 3.99999ZM13.4319 3.99999L12.6327 1.59999H15.7191L17.7195 3.99999H13.4319ZM5.1999 18.4V12.4H8.7999V18.4H5.1999Z"
                                  fill="white"></path>
                              </svg>

                            </span>
                            <span class="text">
                              Add Shop
                            </span>
                          </li>
                          <li class="list-item" @click="supplyPopOpn">
                            <span class="icon">
                              <svg width="16" height="20" viewBox="0 0 16 20" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" clip-rule="evenodd"
                                  d="M15.84 16.1931C15.84 19.4891 11.32 19.8701 7.921 19.8701L7.67776 19.8699C5.51221 19.8646 0 19.7279 0 16.1731C0 12.9444 4.33835 12.5129 7.71148 12.4966L8.16423 12.4963C10.3296 12.5016 15.84 12.6383 15.84 16.1931ZM7.921 13.9961C3.66 13.9961 1.5 14.7281 1.5 16.1731C1.5 17.6311 3.66 18.3701 7.921 18.3701C12.181 18.3701 14.34 17.6381 14.34 16.1931C14.34 14.7351 12.181 13.9961 7.921 13.9961ZM7.921 -0.000305176C10.849 -0.000305176 13.23 2.38169 13.23 5.30969C13.23 8.23769 10.849 10.6187 7.921 10.6187H7.889C4.967 10.6097 2.6 8.2267 2.60997 5.30669C2.60997 2.3817 4.992 -0.000305176 7.921 -0.000305176ZM7.921 1.42769C5.78 1.42769 4.03798 3.16869 4.03798 5.30969C4.031 7.4437 5.76 9.18369 7.892 9.1917L7.921 9.90569V9.1917C10.061 9.1917 11.802 7.44969 11.802 5.30969C11.802 3.16869 10.061 1.42769 7.921 1.42769Z"
                                  fill="white"></path>
                              </svg>
                            </span>
                            <span class="text">
                              Add Supplier
                            </span>
                          </li>
                          <li class="list-item" @click="discPopOpn">
                            <span class="icon">
                              <svg width="22" height="18" viewBox="0 0 22 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" clip-rule="evenodd"
                                  d="M17.451 -0.000289917C19.683 -0.000289917 21.499 1.79771 21.499 4.00671L21.5 6.60071C21.5 6.79871 21.421 6.99071 21.28 7.13071C21.14 7.27171 20.949 7.35071 20.75 7.35071C19.963 7.35071 19.323 7.97871 19.323 8.75071C19.323 9.52271 19.963 10.1507 20.75 10.1507C21.164 10.1507 21.5 10.4867 21.5 10.9007V13.4927C21.5 15.7017 19.684 17.4997 17.452 17.4997H4.048C1.816 17.4997 0 15.7017 0 13.4927V10.9007C0 10.4867 0.336 10.1507 0.75 10.1507C1.537 10.1507 2.177 9.52271 2.177 8.75071C2.177 8.00071 1.563 7.43471 0.75 7.43471C0.551 7.43471 0.36 7.35571 0.22 7.21471C0.079 7.07471 0 6.88271 0 6.68471L0.001 4.00671C0.001 1.79771 1.817 -0.000289917 4.049 -0.000289917H17.451ZM17.451 1.49971H13.349L13.3496 3.42091C13.3496 3.83491 13.0136 4.17091 12.5996 4.17091C12.1856 4.17091 11.8496 3.83491 11.8496 3.42091L11.849 1.49971H4.049C2.644 1.49971 1.501 2.62471 1.501 4.00671L1.5 6.02471C2.767 6.33571 3.677 7.42171 3.677 8.75071C3.677 10.0927 2.751 11.2247 1.5 11.5537V13.4927C1.5 14.8747 2.643 15.9997 4.048 15.9997H11.849L11.8496 14.5112C11.8496 14.0962 12.1856 13.7612 12.5996 13.7612C13.0136 13.7612 13.3496 14.0962 13.3496 14.5112L13.349 15.9997H17.452C18.857 15.9997 20 14.8747 20 13.4927V11.5537C18.749 11.2247 17.823 10.0927 17.823 8.75071C17.823 7.40771 18.748 6.27671 20 5.94771L19.999 4.00671C19.999 2.62471 18.856 1.49971 17.451 1.49971ZM12.5996 5.50421C13.0136 5.50421 13.3496 5.84021 13.3496 6.25421V11.0752C13.3496 11.4892 13.0136 11.8252 12.5996 11.8252C12.1856 11.8252 11.8496 11.4892 11.8496 11.0752V6.25421C11.8496 5.84021 12.1856 5.50421 12.5996 5.50421Z"
                                  fill="white"></path>
                              </svg>
                            </span>
                            <span class="text">
                              Set Discount
                            </span>
                          </li>
                        </ul>

                      </div>
                      <!-- modal content end -->
                    </div>
                  </div>
                </div>
              </div>
    </div>
</template>

<script>
export default {
    name: 'BaparibazarUpdatePlusIcon',

    data() {
        return {
            showMenu: false
        };
    },

    mounted() {

    },

    methods: {
        customerPopOpn() {
            document.getElementById("shop_keeper").style.width = "610px";
            this.showMenu = false;
        },
        plusIcon() {
            this.showMenu = !this.showMenu;
        },
        addProdOnePopOpn() {
            document.getElementById("add_product_one").style.width = "610px";
            this.showMenu = false;
        },
        supplyPopOpn() {
            document.getElementById("supplyers").style.width = "610px";
            this.showMenu = false;
        },
        discPopOpn() {
            document.getElementById("discount_pop").style.width = "610px";
            this.showMenu = false;
        }

    },
};
</script>

<style lang="scss" scoped>

</style>