<template>
  <div class="bg-white">
    <!-- Hero Section -->
    <div class="relative bg-gradient-to-r from-blue-600 to-indigo-700">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24">
        <div class="text-center">
          <h1 class="text-4xl tracking-tight font-extrabold text-white sm:text-5xl md:text-6xl">
            <span class="block">CloudTix 云票据</span>
            <span class="block text-blue-200 mt-2 text-2xl sm:text-3xl md:text-4xl">收集每一张电影票与火车票，留住生活每一段精彩</span>
          </h1>
          <p class="mt-6 max-w-2xl mx-auto text-xl text-blue-100">
            拍照即可智能录入，地图回顾旅程足迹，与票根合影分享 —— 让每一张票根都成为可珍藏的回忆。
          </p>
          <div class="mt-10 flex flex-col sm:flex-row justify-center items-center gap-4">
            <a
              href="https://apps.apple.com/us/app/cloudtix/id6754343145"
              target="_blank"
              rel="noopener"
              class="inline-flex items-center gap-2 px-8 py-3 border border-transparent text-base font-medium rounded-md text-blue-700 bg-white hover:bg-blue-50 md:py-4 md:text-lg md:px-10"
            >
              <svg class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
                <path d="M16.365 1.43c0 1.14-.41 2.21-1.23 3.13-.99 1.11-2.17 1.74-3.41 1.65-.14-1.12.41-2.27 1.21-3.16.91-1.02 2.36-1.74 3.43-1.62zM20.5 17.21c-.56 1.29-.83 1.87-1.55 3.01-.99 1.58-2.4 3.55-4.13 3.57-1.54.02-1.94-1-4.04-.99-2.1.01-2.54 1.01-4.08.99-1.74-.02-3.07-1.81-4.06-3.39-2.77-4.41-3.06-9.59-1.35-12.35 1.21-1.94 3.13-3.08 4.93-3.08 1.84 0 2.99.99 4.51.99 1.47 0 2.36-1 4.49-1 1.61 0 3.32.88 4.54 2.4-3.99 2.18-3.34 7.87.74 8.85z" />
              </svg>
              App Store
            </a>
            <button
              type="button"
              disabled
              class="inline-flex items-center gap-2 px-8 py-3 border border-white text-base font-medium rounded-md text-white/80 bg-white/10 cursor-not-allowed md:py-4 md:text-lg md:px-10"
            >
              <svg class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
                <path d="M3.609 1.814L13.792 12 3.61 22.186a.996.996 0 01-.61-.92V2.734c0-.394.23-.736.61-.92zm10.89 10.893l2.302 2.302-10.937 6.235 8.635-8.537zM21.61 9.836c.594.348.594 1.18 0 1.528l-2.32 1.325-2.535-2.589 2.535-2.589 2.32 1.325zM5.864 2.422l10.937 6.235-2.302 2.302L5.864 2.422z" />
              </svg>
              Google Play · 即将上线
            </button>
          </div>
          <p class="mt-6 text-sm text-blue-200">
            目前支持 iOS · Android 版本敬请期待
          </p>
        </div>
      </div>
    </div>

    <!-- How It Works Section -->
    <div class="py-16 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center">
          <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
            三步，把票根变成回忆
          </h2>
          <p class="mt-4 max-w-2xl mx-auto text-xl text-gray-500">
            从录入到回顾，一个 App 走完完整闭环
          </p>
        </div>

        <div class="mt-16 grid grid-cols-1 gap-8 md:grid-cols-3">
          <!-- Step 1 -->
          <div class="text-center">
            <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-blue-100 text-blue-600 text-2xl font-bold">
              1
            </div>
            <h3 class="mt-6 text-xl font-semibold text-gray-900">智能录入</h3>
            <p class="mt-3 text-gray-500">
              拍照 OCR 自动识别票面信息，或二维码扫码秒建，无需手动逐项填写。
            </p>
          </div>

          <!-- Step 2 -->
          <div class="text-center">
            <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-blue-100 text-blue-600 text-2xl font-bold">
              2
            </div>
            <h3 class="mt-6 text-xl font-semibold text-gray-900">分类管理</h3>
            <p class="mt-3 text-gray-500">
              「即将到来」优先展示未出行的票，「我的库」沉淀所有历史票根，一目了然。
            </p>
          </div>

          <!-- Step 3 -->
          <div class="text-center">
            <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-blue-100 text-blue-600 text-2xl font-bold">
              3
            </div>
            <h3 class="mt-6 text-xl font-semibold text-gray-900">回顾分享</h3>
            <p class="mt-3 text-gray-500">
              旅程地图记录足迹，与票根合影留念，Live Activities 锁屏实时提醒。
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Features Section -->
    <div class="py-16 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center">
          <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
            为什么选择 CloudTix
          </h2>
          <p class="mt-4 max-w-2xl mx-auto text-xl text-gray-500">
            不只是票据管理工具，更是属于你的生活足迹收藏
          </p>
        </div>

        <div class="mt-16">
          <div class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
            <!-- Feature 1: OCR -->
            <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition-shadow">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white mb-4">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z" />
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z" />
                </svg>
              </div>
              <h3 class="text-lg font-medium text-gray-900">AI 智能识别</h3>
              <p class="mt-2 text-gray-500">
                拍照或上传电影票、火车票图片，自动提取影院、场次、车次、座位等信息，一键填表。
              </p>
            </div>

            <!-- Feature 2: QR Scan -->
            <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition-shadow">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white mb-4">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v1m6 11h2m-6 0h-2v4m0-11v3m0 0h.01M12 12h4.01M16 20h4M4 12h4m12 0h.01M5 8h2a1 1 0 001-1V5a1 1 0 00-1-1H5a1 1 0 00-1 1v2a1 1 0 001 1zm12 0h2a1 1 0 001-1V5a1 1 0 00-1-1h-2a1 1 0 00-1 1v2a1 1 0 001 1zM5 20h2a1 1 0 001-1v-2a1 1 0 00-1-1H5a1 1 0 00-1 1v2a1 1 0 001 1z" />
                </svg>
              </div>
              <h3 class="text-lg font-medium text-gray-900">二维码扫描</h3>
              <p class="mt-2 text-gray-500">
                直接扫描车票或取票码上的二维码，秒速创建票据，免去手动输入。
              </p>
            </div>

            <!-- Feature 3: Travel Map -->
            <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition-shadow">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white mb-4">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7" />
                </svg>
              </div>
              <h3 class="text-lg font-medium text-gray-900">我的足迹地图</h3>
              <p class="mt-2 text-gray-500">
                所有火车旅程在地图上可视化呈现，统计总里程、行程数与到访城市，旅行故事一目了然。
              </p>
            </div>

            <!-- Feature 4: Stub Photo -->
            <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition-shadow">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white mb-4">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z" />
                </svg>
              </div>
              <div class="flex items-center gap-2">
                <h3 class="text-lg font-medium text-gray-900">票根合影</h3>
                <span class="inline-flex items-center px-2 py-0.5 rounded text-xs font-medium bg-gray-100 text-gray-600">iOS</span>
              </div>
              <p class="mt-2 text-gray-500">
                基于 iOS 原生人像分割，让你与电影票、火车票自由合照，缩放旋转随心拖拽，保存珍藏瞬间。
              </p>
            </div>

            <!-- Feature 5: Live Activities -->
            <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition-shadow">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white mb-4">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
                </svg>
              </div>
              <div class="flex items-center gap-2">
                <h3 class="text-lg font-medium text-gray-900">锁屏实时提醒</h3>
                <span class="inline-flex items-center px-2 py-0.5 rounded text-xs font-medium bg-gray-100 text-gray-600">iOS</span>
              </div>
              <p class="mt-2 text-gray-500">
                Live Activities 让票据倒计时直达 iPhone 锁屏与灵动岛，重要行程不再错过。
              </p>
            </div>

            <!-- Feature 6: Cloud Sync -->
            <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition-shadow">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white mb-4">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
                </svg>
              </div>
              <h3 class="text-lg font-medium text-gray-900">云端备份 · 隐私安全</h3>
              <p class="mt-2 text-gray-500">
                票根图片云端备份，换设备也不丢失；数据加密存储，严格保护个人隐私。
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Use Cases Section -->
    <div class="py-16 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
          <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
            适用场景
          </h2>
        </div>

        <div class="grid grid-cols-1 gap-8 md:grid-cols-2">
          <div class="flex items-start">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 4v16M17 4v16M3 8h4m10 0h4M3 12h18M3 16h4m10 0h4M4 20h16a1 1 0 001-1V5a1 1 0 00-1-1H4a1 1 0 00-1 1v14a1 1 0 001 1z" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <h3 class="text-lg font-medium text-gray-900">影迷 & 观影党</h3>
              <p class="mt-2 text-gray-500">
                拍照识别一秒录入电影票，留下海报合影与场次记录，年终自动生成专属观影档案。
              </p>
            </div>
          </div>

          <div class="flex items-start">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <h3 class="text-lg font-medium text-gray-900">旅行家</h3>
              <p class="mt-2 text-gray-500">
                历次火车旅程在地图上自动连线，统计总里程与到访城市，让每一段远行都看得见。
              </p>
            </div>
          </div>

          <div class="flex items-start">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <h3 class="text-lg font-medium text-gray-900">通勤 & 返乡族</h3>
              <p class="mt-2 text-gray-500">
                高频火车出行整齐归档，「即将到来」一目了然，灵动岛实时提醒，不再翻短信找车次。
              </p>
            </div>
          </div>

          <div class="flex items-start">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-500 text-white">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <h3 class="text-lg font-medium text-gray-900">情侣 & 纪念日收藏家</h3>
              <p class="mt-2 text-gray-500">
                每一张共同看过的电影、走过的旅程都留下合影与笔记，把重要时刻打包成可回看的相册。
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA Section -->
    <div class="bg-blue-600">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div class="text-center">
          <h2 class="text-3xl font-extrabold text-white sm:text-4xl">
            开始你的票根收藏之旅
          </h2>
          <p class="mt-4 text-xl text-blue-100">
            免费下载 CloudTix，让每一张电影票与火车票都成为可珍藏的回忆
          </p>
          <div class="mt-8 flex flex-col sm:flex-row justify-center items-center gap-4">
            <a
              href="https://apps.apple.com/us/app/cloudtix/id6754343145"
              target="_blank"
              rel="noopener"
              class="inline-flex items-center gap-2 px-8 py-3 border border-transparent text-base font-medium rounded-md text-blue-600 bg-white hover:bg-blue-50 md:py-4 md:text-lg md:px-10"
            >
              <svg class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
                <path d="M16.365 1.43c0 1.14-.41 2.21-1.23 3.13-.99 1.11-2.17 1.74-3.41 1.65-.14-1.12.41-2.27 1.21-3.16.91-1.02 2.36-1.74 3.43-1.62zM20.5 17.21c-.56 1.29-.83 1.87-1.55 3.01-.99 1.58-2.4 3.55-4.13 3.57-1.54.02-1.94-1-4.04-.99-2.1.01-2.54 1.01-4.08.99-1.74-.02-3.07-1.81-4.06-3.39-2.77-4.41-3.06-9.59-1.35-12.35 1.21-1.94 3.13-3.08 4.93-3.08 1.84 0 2.99.99 4.51.99 1.47 0 2.36-1 4.49-1 1.61 0 3.32.88 4.54 2.4-3.99 2.18-3.34 7.87.74 8.85z" />
              </svg>
              App Store
            </a>
            <button
              type="button"
              disabled
              class="inline-flex items-center gap-2 px-8 py-3 border border-white text-base font-medium rounded-md text-white/80 bg-white/10 cursor-not-allowed md:py-4 md:text-lg md:px-10"
            >
              <svg class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
                <path d="M3.609 1.814L13.792 12 3.61 22.186a.996.996 0 01-.61-.92V2.734c0-.394.23-.736.61-.92zm10.89 10.893l2.302 2.302-10.937 6.235 8.635-8.537zM21.61 9.836c.594.348.594 1.18 0 1.528l-2.32 1.325-2.535-2.589 2.535-2.589 2.32 1.325zM5.864 2.422l10.937 6.235-2.302 2.302L5.864 2.422z" />
              </svg>
              Google Play · 即将上线
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
</content>
</invoke>