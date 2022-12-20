<template>
  <div>
    <div class="container-scroller">
      <!-- sidebar area start -->
      <Sidebar />
      <!-- sidebar area end -->

      <!-- main body area start -->
      <div class="container-fluid main-body">
        <!-- top bar area start -->
        <div class="topbar-area-wrapper">
          <div class="row">
            <div class="col-lg-4">
              <div class="left-content">
                <h3 class="page-title">order</h3>
                <div class="date-and-time">
                  <span class="date">Jun 21, 2021</span>
                  <span class="time">5:32 PM</span>
                </div>
              </div>
            </div>
            <div class="col-lg-8">
              <div class="right-content">
              
              <plus-icon></plus-icon>
            </div>
            </div>
          </div>
        </div>
        <!-- top bar area end -->

        <!-- main body content start -->
        <div class="main-body-content-area-wrapper">
          <order-com></order-com>
        </div>
        <!-- main body content end -->

        <!-- all big popup wrapper start -->
        <AllPopup />
        <!-- all big popup wrapper end -->

      </div>
      <!-- main body area start -->
    </div>
  </div>
</template>
<script>
import Sidebar from '@/components/nav_top/Sidebar.vue';
import Topbar from '@/components/nav_top/Topbar.vue';
import AllPopup from '@/components/all_popup/AllPopup.vue';
import OrderCom from '@/components/pages_component/OrderCom.vue';
import PlusIcon from '@/components/utils/PlusIcon.vue';
export default {
  name: "Order",
  data() {
    return {
    };
  },
  components: {
    Sidebar,
    Topbar,
    AllPopup,
    OrderCom,
    PlusIcon
  },
}
</script>