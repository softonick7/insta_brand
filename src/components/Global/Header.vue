<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <Popover class="relative bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <div class="flex justify-between items-center border-b-2 border-gray-100 py-6 md:justify-start md:space-x-10">
        <div class="flex justify-start lg:w-0 lg:flex-1">
          <a href="#">
            <span class="sr-only">Instantty</span>
            <!-- <img class="h-8 w-auto sm:h-10" src="https://tailwindui.com/img/logos/workflow-mark-amber-400.svg" alt="" /> -->
          <svg xmlns="http://www.w3.org/2000/svg" width="164" height="68" viewBox="0 0 164 68" fill="none">
          <path d="M40.0113 47.922C40.0113 48.23 39.9013 48.4867 39.6813 48.692C39.4613 48.8973 39.2047 49 38.9113 49C38.5887 49 38.3247 48.8973 38.1193 48.692C37.9287 48.4867 37.8333 48.23 37.8333 47.922V34.656C37.8333 34.3627 37.936 34.1133 38.1413 33.908C38.3467 33.7027 38.6107 33.6 38.9333 33.6C39.2267 33.6 39.476 33.7027 39.6813 33.908C39.9013 34.1133 40.0113 34.3627 40.0113 34.656V47.922ZM49.2656 37.208C51.9056 37.208 53.2256 38.792 53.2256 41.96V47.944C53.2256 48.2373 53.1229 48.4867 52.9176 48.692C52.7269 48.8973 52.4776 49 52.1696 49C51.8763 49 51.6269 48.8973 51.4216 48.692C51.2309 48.4867 51.1356 48.2373 51.1356 47.944V41.982C51.1356 41.1167 50.9376 40.4273 50.5416 39.914C50.1456 39.4007 49.5003 39.144 48.6056 39.144C48.0189 39.144 47.4836 39.276 46.9996 39.54C46.5303 39.7893 46.1563 40.134 45.8776 40.574C45.6136 40.9993 45.4816 41.4687 45.4816 41.982V47.944C45.4816 48.2373 45.3789 48.4867 45.1736 48.692C44.9829 48.8973 44.7336 49 44.4256 49C44.1176 49 43.8683 48.9047 43.6776 48.714C43.4869 48.5087 43.3916 48.252 43.3916 47.944V38.528C43.3916 38.2347 43.4869 37.9853 43.6776 37.78C43.8829 37.5747 44.1323 37.472 44.4256 37.472C44.7336 37.472 44.9829 37.5747 45.1736 37.78C45.3789 37.9853 45.4816 38.2347 45.4816 38.528V39.298C45.8629 38.7113 46.3909 38.22 47.0656 37.824C47.7549 37.4133 48.4883 37.208 49.2656 37.208ZM55.6867 47.196C55.5547 46.9907 55.4887 46.7927 55.4887 46.602C55.4887 46.3087 55.6427 46.0593 55.9507 45.854C56.0973 45.7513 56.266 45.7 56.4567 45.7C56.7207 45.7 56.9627 45.81 57.1827 46.03C57.6227 46.5287 58.092 46.9027 58.5907 47.152C59.104 47.4013 59.7127 47.526 60.4167 47.526C60.974 47.5113 61.4653 47.3867 61.8907 47.152C62.316 46.9027 62.5287 46.5067 62.5287 45.964C62.5287 45.4653 62.3087 45.084 61.8687 44.82C61.4433 44.556 60.8127 44.314 59.9767 44.094C59.1553 43.874 58.4733 43.6467 57.9307 43.412C57.388 43.1627 56.926 42.8107 56.5447 42.356C56.178 41.8867 55.9947 41.278 55.9947 40.53C55.9947 39.87 56.178 39.2907 56.5447 38.792C56.926 38.2933 57.4247 37.9047 58.0407 37.626C58.6713 37.3473 59.3533 37.208 60.0867 37.208C60.7907 37.208 61.4873 37.34 62.1767 37.604C62.8807 37.868 63.4527 38.2713 63.8927 38.814C64.0687 39.0193 64.1567 39.232 64.1567 39.452C64.1567 39.6867 64.0393 39.914 63.8047 40.134C63.658 40.266 63.4747 40.332 63.2547 40.332C62.9907 40.332 62.778 40.244 62.6167 40.068C62.3087 39.716 61.9273 39.4447 61.4727 39.254C61.0327 39.0633 60.5413 38.968 59.9987 38.968C59.4413 38.968 58.9647 39.0853 58.5687 39.32C58.1873 39.54 57.9967 39.9213 57.9967 40.464C58.0113 40.9773 58.2313 41.3587 58.6567 41.608C59.0967 41.8573 59.764 42.0993 60.6587 42.334C61.436 42.5393 62.0813 42.7593 62.5947 42.994C63.108 43.2287 63.5407 43.5807 63.8927 44.05C64.2447 44.5047 64.4207 45.106 64.4207 45.854C64.4207 46.5433 64.2227 47.1447 63.8267 47.658C63.4307 48.1567 62.91 48.5453 62.2647 48.824C61.634 49.088 60.9593 49.22 60.2407 49.22C59.3167 49.22 58.4587 49.0587 57.6667 48.736C56.8893 48.4133 56.2293 47.9 55.6867 47.196ZM84.5385 37.318C84.8465 37.318 85.0958 37.4207 85.2865 37.626C85.4918 37.8167 85.5945 38.0733 85.5945 38.396V47.944C85.5945 48.2373 85.4918 48.4867 85.2865 48.692C85.0958 48.8973 84.8465 49 84.5385 49C84.2305 49 83.9811 48.9047 83.7905 48.714C83.5998 48.5087 83.5045 48.252 83.5045 47.944V47.372C83.1231 47.8853 82.6025 48.3253 81.9425 48.692C81.2825 49.044 80.5711 49.22 79.8085 49.22C78.8111 49.22 77.9018 48.9633 77.0805 48.45C76.2738 47.9367 75.6358 47.2253 75.1665 46.316C74.7118 45.392 74.4845 44.358 74.4845 43.214C74.4845 42.07 74.7118 41.0433 75.1665 40.134C75.6358 39.21 76.2738 38.4913 77.0805 37.978C77.8871 37.4647 78.7745 37.208 79.7425 37.208C80.5198 37.208 81.2385 37.3693 81.8985 37.692C82.5731 38.0147 83.1085 38.4253 83.5045 38.924V38.396C83.5045 38.088 83.5998 37.8313 83.7905 37.626C83.9811 37.4207 84.2305 37.318 84.5385 37.318ZM80.0505 47.284C80.7398 47.284 81.3485 47.108 81.8765 46.756C82.4191 46.404 82.8371 45.92 83.1305 45.304C83.4385 44.688 83.5925 43.9913 83.5925 43.214C83.5925 42.4513 83.4385 41.762 83.1305 41.146C82.8371 40.53 82.4191 40.046 81.8765 39.694C81.3485 39.3273 80.7398 39.144 80.0505 39.144C79.3611 39.144 78.7451 39.32 78.2025 39.672C77.6745 40.024 77.2565 40.508 76.9485 41.124C76.6551 41.74 76.5085 42.4367 76.5085 43.214C76.5085 43.9913 76.6551 44.688 76.9485 45.304C77.2565 45.92 77.6745 46.404 78.2025 46.756C78.7451 47.108 79.3611 47.284 80.0505 47.284ZM94.5761 37.208C97.2161 37.208 98.5361 38.792 98.5361 41.96V47.944C98.5361 48.2373 98.4335 48.4867 98.2281 48.692C98.0375 48.8973 97.7881 49 97.4801 49C97.1868 49 96.9375 48.8973 96.7321 48.692C96.5415 48.4867 96.4461 48.2373 96.4461 47.944V41.982C96.4461 41.1167 96.2481 40.4273 95.8521 39.914C95.4561 39.4007 94.8108 39.144 93.9161 39.144C93.3295 39.144 92.7941 39.276 92.3101 39.54C91.8408 39.7893 91.4668 40.134 91.1881 40.574C90.9241 40.9993 90.7921 41.4687 90.7921 41.982V47.944C90.7921 48.2373 90.6895 48.4867 90.4841 48.692C90.2935 48.8973 90.0441 49 89.7361 49C89.4281 49 89.1788 48.9047 88.9881 48.714C88.7975 48.5087 88.7021 48.252 88.7021 47.944V38.528C88.7021 38.2347 88.7975 37.9853 88.9881 37.78C89.1935 37.5747 89.4428 37.472 89.7361 37.472C90.0441 37.472 90.2935 37.5747 90.4841 37.78C90.6895 37.9853 90.7921 38.2347 90.7921 38.528V39.298C91.1735 38.7113 91.7015 38.22 92.3761 37.824C93.0655 37.4133 93.7988 37.208 94.5761 37.208ZM126.952 37.362C127.26 37.362 127.509 37.4647 127.7 37.67C127.905 37.8753 128.008 38.1247 128.008 38.418V47.922C128.008 49.7553 127.502 51.1267 126.49 52.036C125.478 52.9453 124.143 53.4 122.486 53.4C121.943 53.4 121.408 53.3487 120.88 53.246C120.352 53.1433 119.919 53.004 119.582 52.828C119.039 52.5787 118.768 52.2413 118.768 51.816C118.768 51.7427 118.783 51.6473 118.812 51.53C118.9 51.2807 119.025 51.09 119.186 50.958C119.347 50.826 119.531 50.76 119.736 50.76C119.853 50.76 119.963 50.782 120.066 50.826C120.521 51.0313 120.924 51.1927 121.276 51.31C121.628 51.4273 122.039 51.486 122.508 51.486C124.781 51.486 125.918 50.32 125.918 47.988V47.548C125.522 48.076 125.009 48.4867 124.378 48.78C123.762 49.0733 123.051 49.22 122.244 49.22C121.027 49.22 120.073 48.8313 119.384 48.054C118.709 47.2767 118.372 46.2573 118.372 44.996V38.418C118.372 38.11 118.467 37.8607 118.658 37.67C118.849 37.4647 119.098 37.362 119.406 37.362C119.714 37.362 119.963 37.4647 120.154 37.67C120.359 37.8753 120.462 38.1247 120.462 38.418V44.446C120.462 45.414 120.675 46.1327 121.1 46.602C121.525 47.0567 122.171 47.284 123.036 47.284C123.872 47.284 124.561 47.02 125.104 46.492C125.647 45.964 125.918 45.282 125.918 44.446V38.418C125.918 38.11 126.013 37.8607 126.204 37.67C126.395 37.4647 126.644 37.362 126.952 37.362Z" fill="black"></path>
          <path d="M20.4979 27.0122H143" stroke="black" stroke-width="3" stroke-linecap="round"></path>
          <path d="M68.5 19V43.6498C68.5 45.187 70.1184 46.1888 71.4927 45.5" stroke="black" stroke-width="2.3" stroke-linecap="round"></path>
          <path d="M104 19V43.6498C104 45.187 105.618 46.1888 106.993 45.5" stroke="black" stroke-width="2.3" stroke-linecap="round"></path>
          <path d="M111 19V43.6498C111 45.187 112.618 46.1888 113.993 45.5" stroke="black" stroke-width="2.3" stroke-linecap="round"></path>
          <path d="M12 18.7447V14.9149C12 13.8617 12.9 13 14 13H18V14.9149H14V18.7447H12Z" fill="#FFAA00"></path>
          <path d="M146 13H150C151.1 13 152 13.8617 152 14.9149V18.7447H150V14.9149H146V13Z" fill="#FFAA00"></path>
          <path d="M146 56.0851H150V52.2553H152V56.0851C152 57.1383 151.1 58 150 58H146V56.0851Z" fill="#FFAA00"></path>
          <path d="M12 52.2553H14V56.0851H18V58H14C12.9 58 12 57.1383 12 56.0851V52.2553Z" fill="#FFAA00"></path>
        </svg>
          </a>
        </div>
        <div class="-mr-2 -my-2 md:hidden">
          <PopoverButton class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
            <span class="sr-only">Open menu</span>
            <MenuIcon class="h-6 w-6" aria-hidden="true" />
          </PopoverButton>
        </div>
        <PopoverGroup as="nav" class="hidden md:flex space-x-10">
          <Popover class="relative" v-slot="{ open }">
            <PopoverButton :class="[open ? 'text-gray-900' : 'text-gray-500', 'group bg-white rounded-md inline-flex items-center text-base font-medium hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500']">
              <span>Solutions</span>
              <ChevronDownIcon :class="[open ? 'text-gray-600' : 'text-gray-400', 'ml-2 h-5 w-5 group-hover:text-gray-500']" aria-hidden="true" />
            </PopoverButton>

            <transition enter-active-class="transition ease-out duration-200" enter-from-class="opacity-0 translate-y-1" enter-to-class="opacity-100 translate-y-0" leave-active-class="transition ease-in duration-150" leave-from-class="opacity-100 translate-y-0" leave-to-class="opacity-0 translate-y-1">
              <PopoverPanel class="absolute z-10 -ml-4 mt-3 transform px-2 w-screen max-w-md sm:px-0 lg:ml-0 lg:left-1/2 lg:-translate-x-1/2">
                <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 overflow-hidden">
                  <div class="relative grid gap-6 bg-white px-5 py-6 sm:gap-8 sm:p-8">
                    <a v-for="item in solutions" :key="item.name" :href="item.href" class="-m-3 p-3 flex items-start rounded-lg hover:bg-gray-50">
                      <component :is="item.icon" class="flex-shrink-0 h-6 w-6 text-amber-400" aria-hidden="true" />
                      <div class="ml-4">
                        <p class="text-base font-medium text-gray-900">
                          {{ item.name }}
                        </p>
                        <p class="mt-1 text-sm text-gray-500">
                          {{ item.description }}
                        </p>
                      </div>
                    </a>
                  </div>
                  <div class="px-5 py-5 bg-gray-50 space-y-6 sm:flex sm:space-y-0 sm:space-x-10 sm:px-8">
                    <div v-for="item in callsToAction" :key="item.name" class="flow-root">
                      <a :href="item.href" class="-m-3 p-3 flex items-center rounded-md text-base font-medium text-gray-900 hover:bg-gray-100">
                        <component :is="item.icon" class="flex-shrink-0 h-6 w-6 text-gray-400" aria-hidden="true" />
                        <span class="ml-3">{{ item.name }}</span>
                      </a>
                    </div>
                  </div>
                </div>
              </PopoverPanel>
            </transition>
          </Popover>

          <a href="#" class="text-base font-medium text-gray-500 hover:text-gray-900">
            Pricing
          </a>
          <a href="#" class="text-base font-medium text-gray-500 hover:text-gray-900">
            Docs
          </a>

          <Popover class="relative" v-slot="{ open }">
            <PopoverButton :class="[open ? 'text-gray-900' : 'text-gray-500', 'group bg-white rounded-md inline-flex items-center text-base font-medium hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500']">
              <span>More</span>
              <ChevronDownIcon :class="[open ? 'text-gray-600' : 'text-gray-400', 'ml-2 h-5 w-5 group-hover:text-gray-500']" aria-hidden="true" />
            </PopoverButton>

            <transition enter-active-class="transition ease-out duration-200" enter-from-class="opacity-0 translate-y-1" enter-to-class="opacity-100 translate-y-0" leave-active-class="transition ease-in duration-150" leave-from-class="opacity-100 translate-y-0" leave-to-class="opacity-0 translate-y-1">
              <PopoverPanel class="absolute z-10 left-1/2 transform -translate-x-1/2 mt-3 px-2 w-screen max-w-md sm:px-0">
                <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 overflow-hidden">
                  <div class="relative grid gap-6 bg-white px-5 py-6 sm:gap-8 sm:p-8">
                    <a v-for="item in resources" :key="item.name" :href="item.href" class="-m-3 p-3 flex items-start rounded-lg hover:bg-gray-50">
                      <component :is="item.icon" class="flex-shrink-0 h-6 w-6 text-amber-400" aria-hidden="true" />
                      <div class="ml-4">
                        <p class="text-base font-medium text-gray-900">
                          {{ item.name }}
                        </p>
                        <p class="mt-1 text-sm text-gray-500">
                          {{ item.description }}
                        </p>
                      </div>
                    </a>
                  </div>
                  <div class="px-5 py-5 bg-gray-50 sm:px-8 sm:py-8">
                    <div>
                      <h3 class="text-sm tracking-wide font-medium text-gray-500 uppercase">
                        Recent Posts
                      </h3>
                      <ul role="list" class="mt-4 space-y-4">
                        <li v-for="post in recentPosts" :key="post.id" class="text-base truncate">
                          <a :href="post.href" class="font-medium text-gray-900 hover:text-gray-700">
                            {{ post.name }}
                          </a>
                        </li>
                      </ul>
                    </div>
                    <div class="mt-5 text-sm">
                      <a href="#" class="font-medium text-amber-400 hover:text-indigo-500"> View all posts <span aria-hidden="true">&rarr;</span></a>
                    </div>
                  </div>
                </div>
              </PopoverPanel>
            </transition>
          </Popover>
        </PopoverGroup>
        <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
          <a href="#" class="whitespace-nowrap text-base font-medium text-gray-500 hover:text-gray-900">
            Sign in
          </a>
          <a href="#" class="ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-amber-400 hover:bg-indigo-700">
            Sign up
          </a>
        </div>
      </div>
    </div>

    <transition enter-active-class="duration-200 ease-out" enter-from-class="opacity-0 scale-95" enter-to-class="opacity-100 scale-100" leave-active-class="duration-100 ease-in" leave-from-class="opacity-100 scale-100" leave-to-class="opacity-0 scale-95">
      <PopoverPanel focus class="absolute top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden">
        <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 bg-white divide-y-2 divide-gray-50">
          <div class="pt-5 pb-6 px-5">
            <div class="flex items-center justify-between">
              <div>
                <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-mark-amber-400.svg" alt="Workflow" />
              </div>
              <div class="-mr-2">
                <PopoverButton class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                  <span class="sr-only">Close menu</span>
                  <XIcon class="h-6 w-6" aria-hidden="true" />
                </PopoverButton>
              </div>
            </div>
            <div class="mt-6">
              <nav class="grid gap-y-8">
                <a v-for="item in solutions" :key="item.name" :href="item.href" class="-m-3 p-3 flex items-center rounded-md hover:bg-gray-50">
                  <component :is="item.icon" class="flex-shrink-0 h-6 w-6 text-amber-400" aria-hidden="true" />
                  <span class="ml-3 text-base font-medium text-gray-900">
                    {{ item.name }}
                  </span>
                </a>
              </nav>
            </div>
          </div>
          <div class="py-6 px-5 space-y-6">
            <div class="grid grid-cols-2 gap-y-4 gap-x-8">
              <a href="#" class="text-base font-medium text-gray-900 hover:text-gray-700">
                Pricing
              </a>

              <a href="#" class="text-base font-medium text-gray-900 hover:text-gray-700">
                Docs
              </a>
              <a v-for="item in resources" :key="item.name" :href="item.href" class="text-base font-medium text-gray-900 hover:text-gray-700">
                {{ item.name }}
              </a>
            </div>
            <div>
              <a href="#" class="w-full flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-amber-400 hover:bg-indigo-700">
                Sign up
              </a>
              <p class="mt-6 text-center text-base font-medium text-gray-500">
                Existing customer?
                {{ ' ' }}
                <a href="#" class="text-amber-400 hover:text-indigo-500">
                  Sign in
                </a>
              </p>
            </div>
          </div>
        </div>
      </PopoverPanel>
    </transition>
  </Popover>
</template>

<script>
import { Popover, PopoverButton, PopoverGroup, PopoverPanel } from '@headlessui/vue'
import {
  BookmarkAltIcon,
  CalendarIcon,
  ChartBarIcon,
  CursorClickIcon,
  MenuIcon,
  PhoneIcon,
  PlayIcon,
  RefreshIcon,
  ShieldCheckIcon,
  SupportIcon,
  ViewGridIcon,
  XIcon,
} from '@heroicons/vue/outline'
import { ChevronDownIcon } from '@heroicons/vue/solid'

const solutions = [
  {
    name: 'Analytics',
    description: 'Get a better understanding of where your traffic is coming from.',
    href: '#',
    icon: ChartBarIcon,
  },
  {
    name: 'Engagement',
    description: 'Speak directly to your customers in a more meaningful way.',
    href: '#',
    icon: CursorClickIcon,
  },
  { name: 'Security', description: "Your customers' data will be safe and secure.", href: '#', icon: ShieldCheckIcon },
  {
    name: 'Integrations',
    description: "Connect with third-party tools that you're already using.",
    href: '#',
    icon: ViewGridIcon,
  },
  {
    name: 'Automations',
    description: 'Build strategic funnels that will drive your customers to convert',
    href: '#',
    icon: RefreshIcon,
  },
]
const callsToAction = [
  { name: 'Watch Demo', href: '#', icon: PlayIcon },
  { name: 'Contact Sales', href: '#', icon: PhoneIcon },
]
const resources = [
  {
    name: 'Help Center',
    description: 'Get all of your questions answered in our forums or contact support.',
    href: '#',
    icon: SupportIcon,
  },
  {
    name: 'Guides',
    description: 'Learn how to maximize our platform to get the most out of it.',
    href: '#',
    icon: BookmarkAltIcon,
  },
  {
    name: 'Events',
    description: 'See what meet-ups and other events we might be planning near you.',
    href: '#',
    icon: CalendarIcon,
  },
  { name: 'Security', description: 'Understand how we take your privacy seriously.', href: '#', icon: ShieldCheckIcon },
]
const recentPosts = [
  { id: 1, name: 'Boost your conversion rate', href: '#' },
  { id: 2, name: 'How to use search engine optimization to drive traffic to your site', href: '#' },
  { id: 3, name: 'Improve your customer experience', href: '#' },
]

export default {
  components: {
    Popover,
    PopoverButton,
    PopoverGroup,
    PopoverPanel,
    ChevronDownIcon,
    MenuIcon,
    XIcon,
  },
  setup() {
    return {
      solutions,
      callsToAction,
      resources,
      recentPosts,
    }
  },
}
</script>