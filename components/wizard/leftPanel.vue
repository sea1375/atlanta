<template>
  <div class="w-left-panel" :class="{ 'mobile-panel-hidden': isMobile }">
    <svg
      width="17"
      height="17"
      viewBox="0 0 17 17"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
      class="close-button"
      @click="closeButton()"
    >
      <path
        fill-rule="evenodd"
        clip-rule="evenodd"
        d="M11.5046 8.50027L16.3769 3.62779C17.2077 2.79694 17.2077 1.45399 16.3769 0.623137C15.5461 -0.207712 14.2031 -0.207712 13.3723 0.623137L8.5 5.49561L3.62768 0.623137C2.79686 -0.207712 1.45394 -0.207712 0.623117 0.623137C-0.207706 1.45399 -0.207706 2.79694 0.623117 3.62779L5.49544 8.50027L0.623117 13.3727C-0.207706 14.2036 -0.207706 15.5465 0.623117 16.3774C1.03747 16.7918 1.58143 17 2.1254 17C2.66936 17 3.21333 16.7918 3.62768 16.3774L8.5 11.5049L13.3723 16.3774C13.7867 16.7918 14.3306 17 14.8746 17C15.4186 17 15.9625 16.7918 16.3769 16.3774C17.2077 15.5465 17.2077 14.2036 16.3769 13.3727L11.5046 8.50027Z"
        fill="white"
      />
    </svg>
    <nuxt-link to="/">
      <svg
        data-v-314f53c6
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 304.44 44.84"
        class="left-column-logo"
        @click="mobileRedirect()"
      >
        <title data-v-314f53c6>Atlanta Meal Prep</title>
        <path
          data-v-314f53c6
          d="M117.45,20.06a2.12,2.12,0,0,0-2.12,2.12v2.94a2.05,2.05,0,0,1-4.1,0v-10a2.12,2.12,0,0,0-4.15-.59,9.22,9.22,0,0,0-14.32,7.7v2.94a2.05,2.05,0,1,1-4.1,0v-23a2.12,2.12,0,1,0-4.24,0V5.88H78.18a2.12,2.12,0,1,0,0,4.24h6.23v15a2.05,2.05,0,0,1-4.11,0V22.18A9.22,9.22,0,0,0,66,14.48a2.12,2.12,0,0,0-4.15.59v10a2.05,2.05,0,1,1-4.1,0v-10a2.12,2.12,0,0,0-4.15-.59,9.22,9.22,0,0,0-14.32,7.7v2.94a2.05,2.05,0,1,1-4.1,0v-23a2.12,2.12,0,1,0-4.24,0v23a2.05,2.05,0,1,1-4.1,0v-23a2.12,2.12,0,1,0-4.24,0V5.88H16.34a2.12,2.12,0,0,0,0,4.24h6.23v15a2.05,2.05,0,1,1-4.1,0v-10a2.12,2.12,0,0,0-4.15-.59,9.24,9.24,0,1,0,1.2,14.45,6.27,6.27,0,0,0,9.18.89,6.26,6.26,0,0,0,8.35,0,6.27,6.27,0,0,0,9.18-.89,9.18,9.18,0,0,0,12.57,0,6.25,6.25,0,0,0,7.69,1.88,2.12,2.12,0,0,0,3.61-1.51V22.18a5,5,0,0,1,10,0v2.94a6.29,6.29,0,0,0,10.47,4.7,6.27,6.27,0,0,0,9.18-.89,9.18,9.18,0,0,0,12.57,0,6.29,6.29,0,0,0,11.3-3.81V22.18A2.12,2.12,0,0,0,117.45,20.06Zm-9.49-5a1.14,1.14,0,1,1,2.28,0v3A9.28,9.28,0,0,0,108,15.15Zm.49,12.24a5.27,5.27,0,0,1-.49-2.19V16.5a8.21,8.21,0,0,1,.49,10.81ZM102,13.93a8.2,8.2,0,0,1,5,1.7v3.29a6,6,0,0,0-11,3.27v2.94a5.27,5.27,0,0,1-.49,2.19A8.24,8.24,0,0,1,102,13.93Zm0,13.24a5,5,0,1,1,5-5A5,5,0,0,1,102,27.17Zm-16.6-25a1.14,1.14,0,0,1,2.28,0V6.22a2.11,2.11,0,0,0-1.14-.34H85.39ZM87.67,8a1.14,1.14,0,0,1-1.14,1.14H85.39V6.86h1.14A1.14,1.14,0,0,1,87.67,8ZM78.18,9.14a1.14,1.14,0,1,1,0-2.28h6.23V9.14Zm7.21,1h1.14a2.11,2.11,0,0,0,1.14-.34V25.12a5.26,5.26,0,0,1-1.14,3.25,5.26,5.26,0,0,1-1.14-3.25Zm-22.57,5a1.14,1.14,0,1,1,2.28,0v.08a9.28,9.28,0,0,0-2.28,2.92Zm-8.35,0a1.14,1.14,0,1,1,2.28,0v3a9.28,9.28,0,0,0-2.28-2.92ZM55,27.31a5.27,5.27,0,0,1-.49-2.19V16.5A8.21,8.21,0,0,1,55,27.31ZM48.5,13.93a8.2,8.2,0,0,1,5,1.69v3.29a6,6,0,0,0-11,3.27v2.94A5.27,5.27,0,0,1,42,27.31,8.24,8.24,0,0,1,48.5,13.93Zm0,13.24a5,5,0,1,1,5-5A5,5,0,0,1,48.5,27.17Zm-16.6-25a1.14,1.14,0,0,1,2.28,0v23A5.26,5.26,0,0,1,33,28.37a5.26,5.26,0,0,1-1.14-3.25Zm-8.35,0a1.14,1.14,0,0,1,2.28,0V6.22a2.1,2.1,0,0,0-1.14-.34H23.55ZM25.83,8a1.14,1.14,0,0,1-1.14,1.14H23.55V6.86h1.14A1.14,1.14,0,0,1,25.83,8ZM16.34,9.14a1.14,1.14,0,0,1,0-2.28h6.23V9.14Zm7.21,1h1.14a2.1,2.1,0,0,0,1.14-.34V25.12a5.26,5.26,0,0,1-1.14,3.25,5.26,5.26,0,0,1-1.14-3.25Zm-8.35,5a1.14,1.14,0,1,1,2.28,0v3a9.28,9.28,0,0,0-2.28-2.92Zm.49,12.24a5.27,5.27,0,0,1-.49-2.19V16.5a8.21,8.21,0,0,1,.49,10.81ZM9.23,30.44a8.25,8.25,0,1,1,5-14.81v3.29a6,6,0,1,0,0,6.51A6.25,6.25,0,0,0,15,28.1,8.22,8.22,0,0,1,9.23,30.44Zm0-3.26a5,5,0,1,1,5-5A5,5,0,0,1,9.23,27.17Zm7,1A9.25,9.25,0,0,0,17.63,26a3,3,0,0,0,5.23,1A6.29,6.29,0,0,0,24,29.11a5.25,5.25,0,0,1-7.79-.9Zm9.18.9A6.29,6.29,0,0,0,26.52,27a3,3,0,0,0,4.69,0,6.29,6.29,0,0,0,1.13,2.09,5.22,5.22,0,0,1-7,0Zm11.83,1.33a5.27,5.27,0,0,1-3.48-1.33A6.29,6.29,0,0,0,34.87,27a3,3,0,0,0,5.23-1,9.25,9.25,0,0,0,1.42,2.21A5.3,5.3,0,0,1,37.21,30.44Zm11.29,0a8.22,8.22,0,0,1-5.74-2.34,6.25,6.25,0,0,0,.74-2.68,6,6,0,0,0,10,0,6.25,6.25,0,0,0,.74,2.68A8.22,8.22,0,0,1,48.5,30.44Zm7-2.23A9.25,9.25,0,0,0,56.9,26a3,3,0,0,0,4.94,1.34v2A2.1,2.1,0,0,0,62,30a5.26,5.26,0,0,1-6.48-1.75Zm9.62,1.08A1.14,1.14,0,0,1,64,30.44a1.11,1.11,0,0,1-.56-.17,6.34,6.34,0,0,0,1.7-1.79Zm-2.25.16a1.07,1.07,0,0,1,0-.16V22.18A8.22,8.22,0,0,1,65.1,16.5v8.62A5.31,5.31,0,0,1,62.85,29.45ZM77,25.12V22.18a6,6,0,0,0-11-3.27V15.62a8.24,8.24,0,0,1,13.24,6.56v2.94A3,3,0,0,0,84.7,27a6.29,6.29,0,0,0,1.13,2.09,5.29,5.29,0,0,1-8.8-4ZM90.7,30.44a5.27,5.27,0,0,1-3.48-1.33A6.29,6.29,0,0,0,88.36,27a3,3,0,0,0,5.23-1A9.25,9.25,0,0,0,95,28.21,5.3,5.3,0,0,1,90.7,30.44Zm11.29,0a8.22,8.22,0,0,1-5.74-2.34A6.25,6.25,0,0,0,97,25.42a6,6,0,0,0,10,0,6.25,6.25,0,0,0,.74,2.68A8.22,8.22,0,0,1,102,30.44Zm16.6-5.32A5.3,5.3,0,0,1,109,28.21,9.25,9.25,0,0,0,110.39,26a3,3,0,0,0,5.92-.88V22.18a1.14,1.14,0,0,1,2.28,0Z"
          fill="#293f94"
        />
        <path
          data-v-314f53c6
          d="M302.51,16.22a9.36,9.36,0,0,0-7.44-3.68,9.32,9.32,0,0,0-5.21,1.59,2.12,2.12,0,0,0-4.17.54V42.72a2.12,2.12,0,1,0,4.24,0v-13a9.37,9.37,0,0,0,12.58-13.54Zm-7.44,10.83a5.13,5.13,0,1,1,0-10.26,5.07,5.07,0,0,1,2.38.58,5.19,5.19,0,0,1,1.7,1.43,5.08,5.08,0,0,1,1.06,3.12A5.14,5.14,0,0,1,295.07,27.05Z"
          fill="#293f94"
        />
        <path
          data-v-314f53c6
          d="M274.25,12.54a9.39,9.39,0,0,0-9.38,9.38v3.4a1.74,1.74,0,1,1-3.47,0V20.56a5,5,0,0,0-4.94-5h-4.6v-.87a5.12,5.12,0,1,0-5.11,5.11h.87v3.41a3.87,3.87,0,1,1-7.73,0V21.92a9.29,9.29,0,0,0-1.93-5.7,9.36,9.36,0,0,0-7.44-3.68,9.32,9.32,0,0,0-5.21,1.59,2.12,2.12,0,0,0-4.17.54V42.72a2.12,2.12,0,1,0,4.24,0v-13a9.33,9.33,0,0,0,12-1.52,8.1,8.1,0,0,0,14.44-5V19.78h4.52a.78.78,0,0,1,.77.78v5h0A6,6,0,0,0,268,28.85a9.33,9.33,0,0,0,6.3,2.45,2.12,2.12,0,0,0,0-4.24,5.14,5.14,0,0,1-4.67-3H281.5a2.12,2.12,0,0,0,2.12-2.12A9.39,9.39,0,0,0,274.25,12.54ZM230.52,27.05a5.13,5.13,0,1,1,0-10.26,5.07,5.07,0,0,1,2.38.58,5.19,5.19,0,0,1,1.7,1.43,5.09,5.09,0,0,1,1.06,3.12A5.14,5.14,0,0,1,230.52,27.05Zm17.11-11.51h-.87a.87.87,0,1,1,.87-.87Zm22,4.26a5.12,5.12,0,0,1,9.34,0Z"
          fill="#293f94"
        />
        <path
          data-v-314f53c6
          d="M167.17,12.67A9.39,9.39,0,0,0,157.79,22v3.4a1.74,1.74,0,1,1-3.47,0V19.29A7.69,7.69,0,0,0,141,14a7.66,7.66,0,0,0-9.36-1.41,2.12,2.12,0,0,0-3.92,1.12V29.29a2.12,2.12,0,1,0,4.24,0v-10a3.46,3.46,0,0,1,6.91,0v10a2.12,2.12,0,1,0,4.24,0v-10a3.46,3.46,0,1,1,6.91,0v6.65h0a6,6,0,0,0,10.77,3,9.33,9.33,0,0,0,6.3,2.45,2.12,2.12,0,0,0,0-4.24,5.14,5.14,0,0,1-4.67-3h11.92A2.12,2.12,0,0,0,176.54,22,9.39,9.39,0,0,0,167.17,12.67Zm-4.67,7.25a5.12,5.12,0,0,1,9.34,0Z"
          fill="#293f94"
        />
        <path
          data-v-314f53c6
          d="M210.83,19.92A2.12,2.12,0,0,0,208.71,22v3.4a1.74,1.74,0,1,1-3.47,0V23.12h0v-21a2.12,2.12,0,1,0-4.24,0V22h0v3.4a1.74,1.74,0,1,1-3.47,0V14.79a2.12,2.12,0,0,0-4.17-.54,9.27,9.27,0,0,0-.86-.51A9.38,9.38,0,1,0,194.45,29a6,6,0,0,0,8.67,1A6,6,0,0,0,213,25.44V22A2.12,2.12,0,0,0,210.83,19.92Zm-22.68,7.25a5.13,5.13,0,0,1,0-10.27,5.07,5.07,0,0,1,2.38.58,5.2,5.2,0,0,1,1.7,1.43A5.08,5.08,0,0,1,193.28,22,5.14,5.14,0,0,1,188.15,27.17Z"
          fill="#293f94"
        />
      </svg>
    </nuxt-link>
    <div class="small-spacer"></div>
    <button class="wizard-cart-btn wizard-btn" @click="goToShoppingCart()">
      Shopping cart
    </button>
    <ul class="wizard-left-menu">
      <li id="link-order-and-menu" class="left-panel-nav" @click="openView(1)">
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M18.4286 20.25C19.0714 20.25 19.5 19.8381 19.5 19.2204V9.95359C19.5 9.6447 19.3929 9.3358 19.0714 9.12988L12.6429 3.98167C12.2143 3.67278 11.6786 3.67278 11.25 3.98167L4.82143 9.12988C4.60714 9.3358 4.5 9.6447 4.5 9.95359V19.2204C4.5 19.8381 4.92857 20.25 5.57143 20.25H9.85714V15.1018H14.1429V20.25H18.4286Z"
            fill="#3C3C3C"
          />
          <mask
            id="mask90"
            mask-type="alpha"
            maskUnits="userSpaceOnUse"
            x="4"
            y="3"
            width="16"
            height="18"
          >
            <path
              d="M18.4286 20.25C19.0714 20.25 19.5 19.8381 19.5 19.2204V9.95359C19.5 9.6447 19.3929 9.3358 19.0714 9.12988L12.6429 3.98167C12.2143 3.67278 11.6786 3.67278 11.25 3.98167L4.82143 9.12988C4.60714 9.3358 4.5 9.6447 4.5 9.95359V19.2204C4.5 19.8381 4.92857 20.25 5.57143 20.25H9.85714V15.1018H14.1429V20.25H18.4286Z"
              fill="white"
            />
          </mask>
          <g mask="url(#mask90)">
            <rect width="24" height="24" fill="#3C3C3C" />
          </g>
        </svg>
        <nuxt-link to>Order and menu</nuxt-link>
      </li>
      <li
        id="link-order-history"
        class="left-panel-nav"
        @click="openView(3)"
        v-if="this.$store.state.logedIn === true"
      >
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="24" height="24" fill="white" />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M12 3.75C16.5563 3.75 20.25 7.44365 20.25 12C20.25 16.5563 16.5563 20.25 12 20.25C7.44365 20.25 3.75 16.5563 3.75 12C3.75 7.44365 7.44365 3.75 12 3.75ZM11.9999 6.5C11.2405 6.5 10.6249 7.11561 10.6249 7.875V12C10.6249 12.3647 10.7698 12.7144 11.0276 12.9723L13.7776 15.7223C14.3146 16.2592 15.1852 16.2592 15.7222 15.7223C16.2592 15.1853 16.2592 14.3147 15.7222 13.7777L13.3749 11.4305V7.875C13.3749 7.11561 12.7593 6.5 11.9999 6.5Z"
            fill="#1A1A1A"
          />
          <mask
            id="mask3333"
            mask-type="alpha"
            maskUnits="userSpaceOnUse"
            x="3"
            y="3"
            width="18"
            height="18"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M12 3.75C16.5563 3.75 20.25 7.44365 20.25 12C20.25 16.5563 16.5563 20.25 12 20.25C7.44365 20.25 3.75 16.5563 3.75 12C3.75 7.44365 7.44365 3.75 12 3.75ZM11.9999 6.5C11.2405 6.5 10.6249 7.11561 10.6249 7.875V12C10.6249 12.3647 10.7698 12.7144 11.0276 12.9723L13.7776 15.7223C14.3146 16.2592 15.1852 16.2592 15.7222 15.7223C16.2592 15.1853 16.2592 14.3147 15.7222 13.7777L13.3749 11.4305V7.875C13.3749 7.11561 12.7593 6.5 11.9999 6.5Z"
              fill="white"
            />
          </mask>
          <g mask="url(#mask3333)">
            <rect width="24" height="24" fill="#3C3C3C" />
          </g>
        </svg>
        <nuxt-link to>History of orders</nuxt-link>
      </li>
      <li id="link-weekly-menu" class="left-panel-nav" @click="openView(8)">
        <svg
          width="18"
          height="18"
          viewBox="0 0 18 18"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          style="margin-left: 6px; transform: translateY(0px) translateX(-4px)"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M5.9059 0.751134V6.93821C5.9059 7.44925 6.4437 7.78163 6.90079 7.55308L9.34316 6.3319L11.7855 7.55308C12.2426 7.78163 12.7804 7.44925 12.7804 6.93821V0.751134L16.5603 0.75C17.3181 0.75 17.9363 1.36658 17.9363 2.12604V15.8728C17.9363 16.6306 17.3197 17.2489 16.5603 17.2489L2.12604 17.25C1.36825 17.25 0.75 16.6334 0.75 15.874V2.12717C0.75 1.36938 1.36658 0.751134 2.12604 0.751134H5.9059ZM13.5827 12.0046V14.7993C13.5827 15.014 13.7477 15.1879 13.9585 15.1879H14.6962C14.9038 15.1879 15.0721 15.0141 15.0721 14.7993V12.0046L15.3988 12.3464C15.5445 12.4988 15.7793 12.5003 15.9283 12.3444L16.45 11.7986C16.5968 11.6451 16.5993 11.3987 16.453 11.2456L14.854 9.57279C14.5631 9.26852 14.0916 9.26852 13.8008 9.57279L12.2018 11.2456C12.0566 11.3975 12.0557 11.6427 12.2048 11.7986L12.7264 12.3444C12.8732 12.4979 13.1107 12.4984 13.256 12.3464L13.5827 12.0046ZM11.4056 0.751302V5.82606L9.65065 4.9486C9.45711 4.85183 9.22931 4.85183 9.03578 4.9486L7.28086 5.82606V0.751302H11.4056Z"
            fill="#3C3C3C"
          />
        </svg>
        <nuxt-link to>Weekly menu</nuxt-link>
      </li>
      <li
        id="link-profile"
        class="left-panel-nav"
        @click="openView(2)"
        v-if="this.$store.state.logedIn === true"
      >
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="24" height="24" fill="white" />
          <path
            d="M18.3125 15.0876L14.8547 12.517C16.0073 11.6173 16.7757 10.332 16.7757 8.78959V7.76135C16.7757 5.31926 14.9828 3.13424 12.5496 3.00571C9.98834 2.87718 7.81126 4.93367 7.81126 7.50429V8.78959C7.81126 10.332 8.57964 11.6173 9.73221 12.517L6.27451 15.2161C5.63419 15.7302 5.25 16.5014 5.25 17.2726V19.7147C5.25 20.4859 5.76225 21 6.53063 21H18.0563C18.8247 21 19.337 20.4859 19.337 19.7147V17.1441C19.337 16.3729 18.9528 15.6017 18.3125 15.0876Z"
            fill="black"
          />
          <mask
            id="mask200"
            mask-type="alpha"
            maskUnits="userSpaceOnUse"
            x="5"
            y="3"
            width="15"
            height="18"
          >
            <path
              d="M18.3125 15.0876L14.8547 12.517C16.0073 11.6173 16.7757 10.332 16.7757 8.78959V7.76135C16.7757 5.31926 14.9828 3.13424 12.5496 3.00571C9.98834 2.87718 7.81126 4.93367 7.81126 7.50429V8.78959C7.81126 10.332 8.57964 11.6173 9.73221 12.517L6.27451 15.2161C5.63419 15.7302 5.25 16.5014 5.25 17.2726V19.7147C5.25 20.4859 5.76225 21 6.53063 21H18.0563C18.8247 21 19.337 20.4859 19.337 19.7147V17.1441C19.337 16.3729 18.9528 15.6017 18.3125 15.0876Z"
              fill="white"
            />
          </mask>
          <g mask="url(#mask200)">
            <rect width="24" height="24" fill="#3C3C3C" />
          </g>
        </svg>
        <nuxt-link to>Profile</nuxt-link>
      </li>
      <li
        id="link-rewards"
        class="left-panel-nav"
        @click="openView(4)"
        v-if="this.$store.state.logedIn === true"
      >
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="24" height="24" fill="white" />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M12.6011 5.00847C12.3694 5.31941 12.1738 5.58182 11.9993 5.71582C11.8263 5.58395 11.6643 5.3389 11.472 5.04795C10.9201 4.21296 10.1183 3 8.08701 3C6.4464 3 5.65033 4.25781 5.88332 4.89569C6.17456 5.67937 6.99003 6.09854 8.32973 6.11677C10.747 6.13499 13.1643 6.13499 15.5816 6.11677C16.9504 6.09854 17.795 5.67937 18.1154 4.93214C18.3775 4.27604 17.4783 3 15.5218 3C14.0981 3 13.2204 4.17754 12.6011 5.00847ZM10.8635 11.4539V8.10462C10.0734 8.10462 9.30348 8.09793 8.54682 8.09134H8.54681H8.5468C7.07197 8.07852 5.64759 8.06613 4.2232 8.10462C3.1165 8.13375 3 8.94922 3 9.56082C3 11.4765 3.43752 11.4719 4.88988 11.4568C5.02731 11.4554 5.17382 11.4539 5.32991 11.4539H7.25209H10.8635ZM10.8635 13.9548V21.4434C10.3665 21.4434 9.87141 21.447 9.37814 21.4507C7.90561 21.4616 6.44941 21.4724 5.00956 21.3851C4.16497 21.3851 4.01935 20.8318 4.01935 20.2493C4.00041 18.7336 4.00611 17.5491 4.01241 16.2408C4.0158 15.538 4.01935 14.7995 4.01935 13.9548H10.8635ZM13.3643 21.5016V13.9548H20.1793V20.2784C20.1793 21.123 19.5095 21.5016 18.7231 21.5016H13.3643ZM13.3643 11.4539V8.10461C13.9496 8.10461 14.5311 8.10278 15.1099 8.10095C16.8354 8.0955 18.5365 8.09012 20.2376 8.13374C21.0608 8.18862 21.005 9.17427 20.9957 9.33674C20.9952 9.34671 20.9948 9.35358 20.9948 9.35694C20.9948 11.5094 20.7766 11.5039 19.2118 11.4643H19.2118C19.0616 11.4605 18.8991 11.4564 18.7231 11.4539H13.3643Z"
            fill="black"
          />
          <mask
            id="mask400"
            mask-type="alpha"
            maskUnits="userSpaceOnUse"
            x="3"
            y="3"
            width="18"
            height="19"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M12.6011 5.00847C12.3694 5.31941 12.1738 5.58182 11.9993 5.71582C11.8263 5.58395 11.6643 5.3389 11.472 5.04795C10.9201 4.21296 10.1183 3 8.08701 3C6.4464 3 5.65033 4.25781 5.88332 4.89569C6.17456 5.67937 6.99003 6.09854 8.32973 6.11677C10.747 6.13499 13.1643 6.13499 15.5816 6.11677C16.9504 6.09854 17.795 5.67937 18.1154 4.93214C18.3775 4.27604 17.4783 3 15.5218 3C14.0981 3 13.2204 4.17754 12.6011 5.00847ZM10.8635 11.4539V8.10462C10.0734 8.10462 9.30348 8.09793 8.54682 8.09134H8.54681H8.5468C7.07197 8.07852 5.64759 8.06613 4.2232 8.10462C3.1165 8.13375 3 8.94922 3 9.56082C3 11.4765 3.43752 11.4719 4.88988 11.4568C5.02731 11.4554 5.17382 11.4539 5.32991 11.4539H7.25209H10.8635ZM10.8635 13.9548V21.4434C10.3665 21.4434 9.87141 21.447 9.37814 21.4507C7.90561 21.4616 6.44941 21.4724 5.00956 21.3851C4.16497 21.3851 4.01935 20.8318 4.01935 20.2493C4.00041 18.7336 4.00611 17.5491 4.01241 16.2408C4.0158 15.538 4.01935 14.7995 4.01935 13.9548H10.8635ZM13.3643 21.5016V13.9548H20.1793V20.2784C20.1793 21.123 19.5095 21.5016 18.7231 21.5016H13.3643ZM13.3643 11.4539V8.10461C13.9496 8.10461 14.5311 8.10278 15.1099 8.10095C16.8354 8.0955 18.5365 8.09012 20.2376 8.13374C21.0608 8.18862 21.005 9.17427 20.9957 9.33674C20.9952 9.34671 20.9948 9.35358 20.9948 9.35694C20.9948 11.5094 20.7766 11.5039 19.2118 11.4643H19.2118C19.0616 11.4605 18.8991 11.4564 18.7231 11.4539H13.3643Z"
              fill="white"
            />
          </mask>
          <g mask="url(#mask400)">
            <rect width="24" height="24" fill="#3C3C3C" />
          </g>
        </svg>
        <nuxt-link to>Rewards & Refferals</nuxt-link>
      </li>
      <li id="link-delivery" class="left-panel-nav" @click="openView(7)">
        <svg
          width="18"
          height="18"
          viewBox="0 0 18 18"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          style="margin-left: 6px; transform: translateY(0px) translateX(-4px)"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M5.9059 0.751134V6.93821C5.9059 7.44925 6.4437 7.78163 6.90079 7.55308L9.34316 6.3319L11.7855 7.55308C12.2426 7.78163 12.7804 7.44925 12.7804 6.93821V0.751134L16.5603 0.75C17.3181 0.75 17.9363 1.36658 17.9363 2.12604V15.8728C17.9363 16.6306 17.3197 17.2489 16.5603 17.2489L2.12604 17.25C1.36825 17.25 0.75 16.6334 0.75 15.874V2.12717C0.75 1.36938 1.36658 0.751134 2.12604 0.751134H5.9059ZM13.5827 12.0046V14.7993C13.5827 15.014 13.7477 15.1879 13.9585 15.1879H14.6962C14.9038 15.1879 15.0721 15.0141 15.0721 14.7993V12.0046L15.3988 12.3464C15.5445 12.4988 15.7793 12.5003 15.9283 12.3444L16.45 11.7986C16.5968 11.6451 16.5993 11.3987 16.453 11.2456L14.854 9.57279C14.5631 9.26852 14.0916 9.26852 13.8008 9.57279L12.2018 11.2456C12.0566 11.3975 12.0557 11.6427 12.2048 11.7986L12.7264 12.3444C12.8732 12.4979 13.1107 12.4984 13.256 12.3464L13.5827 12.0046ZM11.4056 0.751302V5.82606L9.65065 4.9486C9.45711 4.85183 9.22931 4.85183 9.03578 4.9486L7.28086 5.82606V0.751302H11.4056Z"
            fill="#3C3C3C"
          />
        </svg>
        <nuxt-link to>Delivery & Pickup</nuxt-link>
      </li>

      <li class="left-panel-nav" @click="toggleAboutContent()">
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="24" height="24" fill="white" />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M11.9999 17.5C11.2405 17.5 10.6249 16.8844 10.6249 16.125V12C10.6249 11.2406 11.2405 10.625 11.9999 10.625C12.7593 10.625 13.3749 11.2406 13.3749 12V16.125C13.3749 16.8844 12.7593 17.5 11.9999 17.5ZM11.9999 9.25C11.2405 9.25 10.6249 8.6344 10.6249 7.875C10.6249 7.11561 11.2405 6.5 11.9999 6.5C12.7593 6.5 13.3749 7.11561 13.3749 7.875C13.3749 8.6344 12.7593 9.25 11.9999 9.25ZM12 20.25C7.44325 20.25 3.75 16.5554 3.75 12C3.75 7.44325 7.44325 3.75 12 3.75C16.5554 3.75 20.25 7.44325 20.25 12C20.25 16.5554 16.5554 20.25 12 20.25Z"
            fill="#1A1A1A"
          />
          <mask
            id="mask87"
            mask-type="alpha"
            maskUnits="userSpaceOnUse"
            x="3"
            y="3"
            width="18"
            height="18"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M11.9999 17.5C11.2405 17.5 10.6249 16.8844 10.6249 16.125V12C10.6249 11.2406 11.2405 10.625 11.9999 10.625C12.7593 10.625 13.3749 11.2406 13.3749 12V16.125C13.3749 16.8844 12.7593 17.5 11.9999 17.5ZM11.9999 9.25C11.2405 9.25 10.6249 8.6344 10.6249 7.875C10.6249 7.11561 11.2405 6.5 11.9999 6.5C12.7593 6.5 13.3749 7.11561 13.3749 7.875C13.3749 8.6344 12.7593 9.25 11.9999 9.25ZM12 20.25C7.44325 20.25 3.75 16.5554 3.75 12C3.75 7.44325 7.44325 3.75 12 3.75C16.5554 3.75 20.25 7.44325 20.25 12C20.25 16.5554 16.5554 20.25 12 20.25Z"
              fill="white"
            />
          </mask>
          <g mask="url(#mask87)">
            <rect width="24" height="24" fill="#3C3C3C" />
          </g>
        </svg>
        <nuxt-link to>About</nuxt-link>

        <div
          v-show="aboutContent"
          class="show-about-content"
          @click="hideMobile()"
        >
          <!-- <nuxt-link to="/contact">Contact & Policy</nuxt-link> -->
          <nuxt-link to="/gallery">Gallery & Reviews</nuxt-link>
          <!-- <nuxt-link to="/delivery-and-pickup">Delivery & Pickup</nuxt-link> -->
          <nuxt-link to="/references">Partners & References</nuxt-link>
        </div>
      </li>
    </ul>
    <div class="bottom-part">
      <span v-if="this.$store.state.logedIn === true">
        <div class="small-spacer"></div>
        <p class="wizard-logout" @click="logOut">
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect width="24" height="24" fill="white" />
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M4.12995 6.86388L10.1812 3.84808C10.6181 3.57623 11.1884 3.90013 11.1884 4.44288V5.34873H15.6897C16.0575 5.34873 16.3555 5.65884 16.3555 6.04119V8.927C16.3555 9.83785 15.0239 9.83785 15.0239 8.927V6.73365H11.1884V17.1971H15.0239V15.0037C15.0239 14.0931 16.3555 14.0931 16.3555 15.0037V17.8895C16.3555 18.2721 16.0575 18.582 15.6897 18.582H11.1884L11.1858 19.4881C11.1863 19.9888 10.6802 20.331 10.2365 20.1102L4.18524 17.0944C3.93118 16.9968 3.75 16.7425 3.75 16.4447L3.75274 7.48624C3.75297 7.22888 3.89211 6.98222 4.12995 6.86388ZM13.2073 11.088C12.0992 11.088 12.0992 12.8406 13.2073 12.8406H18.1242L17.1699 13.8329C16.3867 14.6475 17.5777 15.8866 18.3612 15.0719L20.7485 12.5887C21.0702 12.2541 21.0971 11.7026 20.7485 11.3399L18.3612 8.85668C17.5777 8.04207 16.3867 9.28109 17.1699 10.0957L18.1242 11.088H13.2073Z"
              fill="black"
            />
            <mask
              id="mask2222"
              mask-type="alpha"
              maskUnits="userSpaceOnUse"
              x="3"
              y="3"
              width="18"
              height="18"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M4.12995 6.86388L10.1812 3.84808C10.6181 3.57623 11.1884 3.90013 11.1884 4.44288V5.34873H15.6897C16.0575 5.34873 16.3555 5.65884 16.3555 6.04119V8.927C16.3555 9.83785 15.0239 9.83785 15.0239 8.927V6.73365H11.1884V17.1971H15.0239V15.0037C15.0239 14.0931 16.3555 14.0931 16.3555 15.0037V17.8895C16.3555 18.2721 16.0575 18.582 15.6897 18.582H11.1884L11.1858 19.4881C11.1863 19.9888 10.6802 20.331 10.2365 20.1102L4.18524 17.0944C3.93118 16.9968 3.75 16.7425 3.75 16.4447L3.75274 7.48624C3.75297 7.22888 3.89211 6.98222 4.12995 6.86388ZM13.2073 11.088C12.0992 11.088 12.0992 12.8406 13.2073 12.8406H18.1242L17.1699 13.8329C16.3867 14.6475 17.5777 15.8866 18.3612 15.0719L20.7485 12.5887C21.0702 12.2541 21.0971 11.7026 20.7485 11.3399L18.3612 8.85668C17.5777 8.04207 16.3867 9.28109 17.1699 10.0957L18.1242 11.088H13.2073Z"
                fill="white"
              />
            </mask>
            <g mask="url(#mask2222)">
              <rect width="24" height="24" fill="#3C3C3C" />
            </g>
          </svg>
          Log out
        </p>
      </span>

      <span v-if="this.$store.state.logedIn === false">
        <div class="small-spacer"></div>
        <p class="wizard-logout" @click="login">
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect width="24" height="24" fill="white" />
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M4.12995 6.86388L10.1812 3.84808C10.6181 3.57623 11.1884 3.90013 11.1884 4.44288V5.34873H15.6897C16.0575 5.34873 16.3555 5.65884 16.3555 6.04119V8.927C16.3555 9.83785 15.0239 9.83785 15.0239 8.927V6.73365H11.1884V17.1971H15.0239V15.0037C15.0239 14.0931 16.3555 14.0931 16.3555 15.0037V17.8895C16.3555 18.2721 16.0575 18.582 15.6897 18.582H11.1884L11.1858 19.4881C11.1863 19.9888 10.6802 20.331 10.2365 20.1102L4.18524 17.0944C3.93118 16.9968 3.75 16.7425 3.75 16.4447L3.75274 7.48624C3.75297 7.22888 3.89211 6.98222 4.12995 6.86388ZM13.2073 11.088C12.0992 11.088 12.0992 12.8406 13.2073 12.8406H18.1242L17.1699 13.8329C16.3867 14.6475 17.5777 15.8866 18.3612 15.0719L20.7485 12.5887C21.0702 12.2541 21.0971 11.7026 20.7485 11.3399L18.3612 8.85668C17.5777 8.04207 16.3867 9.28109 17.1699 10.0957L18.1242 11.088H13.2073Z"
              fill="black"
            />
            <mask
              id="mask2222"
              mask-type="alpha"
              maskUnits="userSpaceOnUse"
              x="3"
              y="3"
              width="18"
              height="18"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M4.12995 6.86388L10.1812 3.84808C10.6181 3.57623 11.1884 3.90013 11.1884 4.44288V5.34873H15.6897C16.0575 5.34873 16.3555 5.65884 16.3555 6.04119V8.927C16.3555 9.83785 15.0239 9.83785 15.0239 8.927V6.73365H11.1884V17.1971H15.0239V15.0037C15.0239 14.0931 16.3555 14.0931 16.3555 15.0037V17.8895C16.3555 18.2721 16.0575 18.582 15.6897 18.582H11.1884L11.1858 19.4881C11.1863 19.9888 10.6802 20.331 10.2365 20.1102L4.18524 17.0944C3.93118 16.9968 3.75 16.7425 3.75 16.4447L3.75274 7.48624C3.75297 7.22888 3.89211 6.98222 4.12995 6.86388ZM13.2073 11.088C12.0992 11.088 12.0992 12.8406 13.2073 12.8406H18.1242L17.1699 13.8329C16.3867 14.6475 17.5777 15.8866 18.3612 15.0719L20.7485 12.5887C21.0702 12.2541 21.0971 11.7026 20.7485 11.3399L18.3612 8.85668C17.5777 8.04207 16.3867 9.28109 17.1699 10.0957L18.1242 11.088H13.2073Z"
                fill="white"
              />
            </mask>
            <g mask="url(#mask2222)">
              <rect width="24" height="24" fill="#3C3C3C" />
            </g>
          </svg>
          Log In
        </p>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMobile: false,
      aboutContent: false,
    }
  },
  mounted() {
    const self = this
    if (window.innerWidth <= 1283) {
      this.isMobile = true
    } else {
      self.isMobile = false
    }

    window.onload = () => {
      if (window.innerWidth <= 1283) {
        self.isMobile = true
      } else {
        self.isMobile = false
      }
    }
    document
      .getElementById('link-order-and-menu')
      .classList.add('left-panel-active')
  },
  created() {
    const self = this
    this.$nuxt.$on('mobile-menu-toggle', () => {
      if (self.isMobile) self.isMobile = false
      else self.isMobile = true
    })
  },
  methods: {
    toggleAboutContent() {
      if (this.aboutContent) this.aboutContent = false
      else this.aboutContent = true
    },
    goToShoppingCart() {
      $nuxt.$emit('toggle-view', 4)
      if (window.innerWidth <= 1282) {
        $nuxt.$emit('mobile-menu-toggle')
      }
      history.pushState(null, null, 'wizard?' + urlParam)
      this.checkIfThePageIsWizard(4)
    },
    logOut() {
      this.$store.commit('setLogedIn', false)
      this.$router.push({
        path: '/',
      })
    },
    login() {
      $nuxt.$emit('mobile-menu-toggle')
      // this.$router.push({
      //   path: '/register',
      // })

      $nuxt.$emit('show-auth-popup')
    },
    hideMobile() {
      if (window.innerWidth <= 1282) {
        $nuxt.$emit('mobile-menu-toggle')
      }
    },
    openView(nbr) {
      this.checkIfThePageIsWizard(nbr)
      if (window.innerWidth <= 1282) {
        $nuxt.$emit('mobile-menu-toggle')
      }
      $nuxt.$emit('wizard-view-changed', nbr)
      this.selectNavItem(nbr)
    },
    selectNavItem(nbr) {
      let navId = null
      let urlParam = 'default'
      // which id to toggle
      switch (nbr) {
        case 1:
          navId = 'link-order-and-menu'
          urlParam = 'order'
          break
        case 2:
          navId = 'link-profile'
          urlParam = 'profile'
          break
        case 3:
          navId = 'link-order-history'
          urlParam = 'order-history'
          break
        case 4:
          navId = 'link-rewards'
          urlParam = 'rewards-and-referals'
          break
        case 7:
          navId = 'link-delivery'
          urlParam = 'delivery-and-pickup'
          break
      }
      const navItems = document.querySelectorAll('.left-panel-nav')

      navItems.forEach((element) => {
        element.classList.remove('left-panel-active')
      })
      history.pushState(null, null, 'wizard?' + urlParam)
      document.getElementById(navId).classList.add('left-panel-active')
    },
    closeButton() {
      $nuxt.$emit('mobile-menu-toggle')
    },
    checkIfThePageIsWizard(nbr = null) {
      // check the page name
      const pathName = window.location.pathname

      if (!pathName.includes('wizard')) {
        let urlAddition = ''
        let urlParam = ''
        let navId = ''
        if (nbr != null) {
          switch (nbr) {
            case 1:
              navId = 'link-order-and-menu'
              urlParam = 'order'
              break
            case 2:
              navId = 'link-profile'
              urlParam = 'profile'
              break
            case 3:
              navId = 'link-order-history'
              urlParam = 'order-history'
              break
            case 4:
              navId = 'link-rewards'
              urlParam = 'rewards-and-referals'
              break
            case 7:
              navId = 'link-delivery'
              urlParam = 'delivery-and-pickup'
              break
          }
          urlAddition += '?' + urlParam
        }

        // redirect to the wizard
        this.$router.push({
          path: '/wizard' + urlAddition,
        })
      }
    },
    mobileRedirect() {
      if (window.innerWidth <= 1282) {
        $nuxt.$emit('mobile-menu-toggle')
      }
    },
  },
}
</script>

<style scoped>
.w-left-panel {
  width: 240px;
  height: 100%;
  background: #ffffff;
  box-shadow: 9px 0px 16px #f6f7fa;
}

.close-button {
  display: none;
}

.bottom-part {
  position: absolute;
  bottom: 0px;
  width: max-content;
  margin-left: 16px;
  /* width: 100%;
  padding-right: 40px; */
}

.wizard-logout svg {
  transform: translateY(-3px);
  vertical-align: top;
}

.wizard-logout {
  font-family: Nunito;
  vertical-align: top;
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 18px;
  letter-spacing: 0.192941px;
  color: #3c3c3c !important;
  cursor: pointer;
  margin-top: 24px;
  margin-left: 6px;
}

.wizard-logout:hover {
  color: #293f94 !important;
}

.bottom-info {
  font-family: Nunito, Arial;
  font-style: normal;
  font-weight: bold;
  font-size: 12px;
  line-height: 16px;
  color: #a4b6c0;
}

.bottom-info a {
  font-family: Nunito, Arial;
  font-style: normal;
  font-weight: bold;
  font-size: 12px;
  line-height: 16px;
  color: #a4b6c0;
}

.left-column-logo {
  padding-top: 25px;
  width: 186px;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.small-spacer {
  height: 1px;
  width: 208px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  background: #293f94;
  opacity: 0.2;
  margin-top: 12px;
}

.wizard-cart-btn {
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 16px;
}

.wizard-left-menu {
  width: 100%;
  padding-left: 0;
  position: relative;
}

.wizard-left-menu li:first-child {
  margin-top: 40px;
}

.wizard-left-menu li {
  list-style-type: none;
  width: 80%;
  display: block;
  margin-left: auto;
  margin-right: auto;
  font-family: Nunito;
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 18px;
  letter-spacing: 0.192941px;
  color: #293f94 !important;
  margin-top: 20px;
}

.active-wizard-left-menu li::before {
  content: '';
  position: absolute;
  left: 0;
  top: -7px;
  height: 32px;
  width: 6px;
  background: #293f94;
  border-radius: 0px 100px 100px 0px;
}

.show-about-content a {
  width: 100%;
  display: block;
  margin-left: 34px;
  margin-top: 24px;
}

.wizard-left-menu li a {
  vertical-align: top;
}

.wizard-left-menu li g rect {
  transition: 180ms ease;
}

.wizard-left-menu li:hover g rect {
  fill: #293f94;
}

.wizard-left-menu li:hover path {
  fill: #293f94;
}

.wizard-left-menu li svg {
  transform: translateY(-4px);
  vertical-align: top;
}

.wizard-left-menu a {
  font-family: Nunito;
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 18px;
  letter-spacing: 0.192941px;
  color: #3c3c3c !important;
  position: relative;
}

.wizard-left-menu a:hover {
  color: #293f94 !important;
}

.left-panel-active a {
  color: #293f94 !important;
}

.left-panel-active g rect {
  fill: #293f94 !important;
}

.left-panel-active path {
  fill: #293f94 !important;
}

.wizard-left-menu a::before {
  content: '';
  position: absolute;
  left: -53px;
  top: -5px;
  opacity: 0;
  width: 6px;
  height: 32px;
  background: #293f94;
  border-radius: 0px 100px 100px 0px;
  transition: 200ms ease;
}

.left-panel-active a::before {
  opacity: 1;
}

@media only screen and (max-width: 1282px) {
  .w-left-panel {
    position: fixed;
    width: 100%;
    height: 100%;
    left: 0px;
    top: 0px;
    z-index: 100;
    transition: 300ms ease;
  }
  .wizard-cart-btn {
    width: calc(100% - 40px);
  }
  .left-column-logo {
    width: 40%;
    margin-left: 26px;
    margin-right: 0px;
  }
  .small-spacer {
    width: calc(100vw - 40px);
  }

  .close-button {
    display: block;
    position: absolute;
    top: 26px;
    right: 26px;
  }
  .close-button path {
    fill: black;
  }
  .wizard-left-menu li {
    width: 100%;
    margin-left: 26px;
  }
  .mobile-panel-hidden {
    left: -100%;
  }
}
</style>
