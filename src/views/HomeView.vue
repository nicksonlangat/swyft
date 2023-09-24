<template>
<div class="flex divide-x font-base pb-5 lg:pb-0">
    <Aside />
    <div class="lg:w-4/5 w-full">
        <div class="flex justify-between lg:hidden mx-5 mt-2">
            <h3 class="text-2xl font-extrabold">Swyft</h3>
            <button>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>

            </button>
        </div>
        <div class="mx-5 mt-10 lg:mt-2 flex items-center justify-between">
            <h3 class="lg:text-2xl font-bold">Dashboard overview</h3>
            <img src="../assets/user.jpeg" class="h-12 w-12 rounded-full">
        </div>
        <div class="hidden lg:flex flex-col lg:flex-row gap-5 mt-5 mx-5">
            <div class="lg:w-3/4 rounded-xl bg-white h-72">
                <div class="p-3 flex justify-between">
                    <div class="flex mt-8 flex-col gap-5">
                        <h3 class="text-3xl ">Get where you need to go using our services.</h3>
                        <p class="text-gray-400 text-sm">Budget-friendly car rentals for road trips, city visits and so much more. Book now and start exploring.</p>
                        <button class="bg-violet-600 w-56 text-white py-2 px-6 rounded-lg">Explore cars</button>
                    </div>
                    <div class="-mt-5">
                        <img src="../assets/driving-removebg-preview.png" />
                    </div>
                </div>
            </div>
            <div class="lg:w-1/4 flex flex-col gap-2 items-center justify-center bg-white rounded-xl h-72">
                <img src="../assets/user.jpeg" class="h-20 w-20 object-cover rounded-full">
                <h3>Nick Langat</h3>
                <p class="text-gray-400 text-xs">nickkipro@langat.com</p>
                <button class="border w-72 lg:w-56 mt-5 border-stone-200 py-2 px-6 rounded-lg">Edit profile</button>

            </div>
        </div>
        <div class="flex flex-col lg:flex-row gap-5 mt-5 mx-5">
            <div class="lg:hidden flex flex-col gap-5">
                <div class="bg-white flex flex-col divide-y divide-stone-100 rounded-xl h-32">
                    <div class="flex justify-between items-center p-3">
                        <div class="flex gap-3 items-center">
                            <span class="bg-violet-100 rounded-full px-1 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 text-violet-600 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                </svg>

                            </span>
                            <h3>Turnover</h3>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 text-stone-500 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
                        </svg>
                    </div>
                    <div class="flex justify-between p-3 items-center">
                        <div>
                            <h3>KES 15,000</h3>
                            <p class="text-gray-400 mt-3 text-sm inline-flex gap-2"><span class="text-violet-500">+45 %</span>from last month</p>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-violet-500 h-8">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941" />
                        </svg>

                    </div>

                </div>
                <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl h-32">
                    <div class="flex justify-between items-center p-3">
                        <div class="flex gap-3 items-center">
                            <span class="bg-green-100 rounded-full px-1 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 text-green-600 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                </svg>

                            </span>
                            <h3>Income</h3>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 text-gray-500 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
                        </svg>
                    </div>
                    <div class="flex justify-between p-3 items-center">
                        <div>
                            <h3>KES 65,000</h3>
                            <p class="text-gray-400 mt-3 text-sm inline-flex gap-2"><span class="text-green-500">+45 %</span>from last month</p>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-green-500 h-8">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941" />
                        </svg>

                    </div>

                </div>
                <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl h-32">
                    <div class="flex justify-between items-center p-3">
                        <div class="flex gap-3 items-center">
                            <span class="bg-red-100 rounded-full px-1 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 text-red-600 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                </svg>

                            </span>
                            <h3>Outcome</h3>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 text-gray-500 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
                        </svg>
                    </div>
                    <div class="flex justify-between p-3 items-center">
                        <div>
                            <h3>KES 45,000</h3>
                            <p class="text-gray-400 mt-3 text-sm inline-flex gap-2"><span class="text-red-500">-12 %</span>from last month</p>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-red-500 h-8">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941" />
                        </svg>

                    </div>

                </div>
            </div>
            <div class="lg:w-3/4 rounded-xl lg:bg-white">
                <div class="flex lg:p-3 lg:ml-2 items-center justify-between">
                    <h3 class="font-bold text-xl">Car Listings</h3>
                    <select class="border py-2 px-6 rounded-lg">
                        <option>This week</option>
                        <option>This month</option>
                        <option>This year</option>
                    </select>
                </div>
                <div class="lg:hidden mt-5 flex flex-col gap-5">
                    <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl pb-2 text-sm">
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">client</h3>
                                <p class="flex gap-2 items-center">
                                    <img src="../assets/user.jpeg" class="h-8 w-8 object-cover rounded-full">
                                    Nick Langat</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">car</h3>
                                <p>MAzda Axela</p>
                            </div>
                        </div>
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">reg no</h3>
                                <p>KDK 650N</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">status</h3>
                                <span class="bg-violet-100 text-violet-500 py-1 text-xs px-4 rounded-md">On going</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl pb-2 text-sm">
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">client</h3>
                                <p class="flex gap-2 items-center ">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-4.jpg" class="h-8 w-8 object-cover rounded-full">
                                    John Adams</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">car</h3>
                                <p>Honda Civic</p>
                            </div>
                        </div>
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">reg no</h3>
                                <p>KDK 543E </p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">status</h3>
                                <span class="bg-green-100 text-green-500 py-1 text-xs px-4 rounded-md">Finished</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl pb-2 text-sm">
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">client</h3>
                                <p class="flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-3.jpg" class="h-8 w-8 object-cover rounded-full">
                                    Jene Andrea</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">car</h3>
                                <p>Suzuki Swift</p>
                            </div>
                        </div>
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">reg no</h3>
                                <p>KDK 990H</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">status</h3>
                                <span class="bg-red-100 text-red-500 py-1 text-xs px-4 rounded-md">Cancelled</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl pb-2 text-sm">
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">client</h3>
                                <p class="flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-2.jpg" class="h-8 w-8 object-cover rounded-full">
                                    William Rice</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">car</h3>
                                <p>Toyota Crown</p>
                            </div>
                        </div>
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">reg no</h3>
                                <p>Toyota Crown</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">status</h3>
                                <span class="bg-green-100 text-green-500 py-1 text-xs px-4 rounded-md">Finished</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl pb-2 text-sm">
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">client</h3>
                                <p class="flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-5.jpg" class="h-8 w-8 object-cover rounded-full">
                                    Lenny Smith</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">car</h3>
                                <p>Mazda CX5</p>
                            </div>
                        </div>
                        <div class="flex p-3 justify-between">
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">reg no</h3>
                                <p>KDA 412W</p>
                            </div>
                            <div class="flex flex-col gap-2">
                                <h3 class="text-gray-400 uppercase">status</h3>
                                <span class="bg-violet-100 text-violet-500 py-1 text-xs px-4 rounded-md">On going</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="hidden lg:block relative overflow-x-auto">
                    <table class="w-full text-sm text-left">
                        <thead class="text-xs uppercase text-gray-400 border-b">
                            <tr>
                                <th scope="col" class="px-6 py-3">
                                    No
                                </th>
                                <th scope="col" class="px-6 py-3">
                                    Client
                                </th>
                                <th scope="col" class="px-6 py-3">
                                    Car
                                </th>
                                <th scope="col" class="px-6 py-3">
                                    Reg No
                                </th>
                                <th scope="col" class="px-6 py-3">
                                    Status
                                </th>
                            </tr>
                        </thead>
                        <tbody class="text-xs">
                            <tr class="bg-white">
                                <th class="px-6 py-4">
                                    1
                                </th>
                                <td class="px-6 py-4 inline-flex gap-2 items-center">
                                    <img src="../assets/user.jpeg" class="h-8 w-8 object-cover rounded-full"> Nick Langat
                                </td>
                                <td class="px-6 py-4">
                                    Mazda Axela
                                </td>
                                <td class="px-6 py-4">
                                    KDK 650N
                                </td>
                                <td class="px-6 py-4">
                                    <span class="bg-violet-100 text-violet-500 py-1 px-4 rounded-md">On going</span>
                                </td>
                            </tr>
                            <tr class="bg-white">
                                <th class="px-6 py-4">
                                    2
                                </th>
                                <td class="px-6 py-4 inline-flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-4.jpg" class="h-8 w-8 object-cover rounded-full"> John Adams
                                </td>
                                <td class="px-6 py-4">
                                    Honda Civic
                                </td>
                                <td class="px-6 py-4">
                                    KDK 543E
                                </td>
                                <td class="px-6 py-4">
                                    <span class="bg-green-100 text-green-500 py-1 px-4 rounded-md">Finished</span>
                                </td>
                            </tr>
                            <tr class="bg-white">
                                <th class="px-6 py-4">
                                    3
                                </th>
                                <td class="px-6 py-4 inline-flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-3.jpg" class="h-8 w-8 object-cover rounded-full"> Jene Andrea
                                </td>
                                <td class="px-6 py-4">
                                    Suzuki Swift
                                </td>
                                <td class="px-6 py-4">
                                    KDK 990H
                                </td>
                                <td class="px-6 py-4">
                                    <span class="bg-red-100 text-red-500 py-1 px-4 rounded-md">Cancelled</span>
                                </td>
                            </tr>
                            <tr class="bg-white">
                                <th class="px-6 py-4">
                                    4
                                </th>
                                <td class="px-6 py-4 inline-flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-2.jpg" class="h-8 w-8 object-cover rounded-full"> William Rice
                                </td>
                                <td class="px-6 py-4">
                                    Toyota Crown
                                </td>
                                <td class="px-6 py-4">
                                    KCK 765R
                                </td>
                                <td class="px-6 py-4">
                                    <span class="bg-green-100 text-green-500 py-1 px-4 rounded-md">Finished</span>
                                </td>
                            </tr>
                            <tr class="bg-white">
                                <th class="px-6 py-4">
                                    5
                                </th>
                                <td class="px-6 py-4 inline-flex gap-2 items-center">
                                    <img src="https:flowbite.com/docs/images/people/profile-picture-5.jpg" class="h-8 w-8 object-cover rounded-full"> Lenny Smith
                                </td>
                                <td class="px-6 py-4">
                                    Mazda CX5
                                </td>
                                <td class="px-6 py-4">
                                    KDA 412W
                                </td>
                                <td class="px-6 py-4">
                                    <span class="bg-violet-100 text-violet-500 py-1 px-4 rounded-md">On going</span>
                                </td>
                            </tr>

                        </tbody>
                    </table>
                </div>

            </div>
            <div class="hidden w-1/4 lg:flex flex-col gap-5">
                <div class="bg-white flex flex-col divide-y divide-stone-100 rounded-xl h-32">
                    <div class="flex justify-between items-center p-3">
                        <div class="flex gap-3 items-center">
                            <span class="bg-violet-100 rounded-full px-1 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 text-violet-600 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                </svg>

                            </span>
                            <h3>Turnover</h3>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 text-stone-500 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
                        </svg>
                    </div>
                    <div class="flex justify-between p-3 items-center">
                        <div>
                            <h3>KES 15,000</h3>
                            <p class="text-gray-400 mt-3 text-sm inline-flex gap-2"><span class="text-violet-500">+45 %</span>from last month</p>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-violet-500 h-8">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941" />
                        </svg>

                    </div>

                </div>
                <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl h-32">
                    <div class="flex justify-between items-center p-3">
                        <div class="flex gap-3 items-center">
                            <span class="bg-green-100 rounded-full px-1 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 text-green-600 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                </svg>

                            </span>
                            <h3>Income</h3>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 text-gray-500 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
                        </svg>
                    </div>
                    <div class="flex justify-between p-3 items-center">
                        <div>
                            <h3>KES 65,000</h3>
                            <p class="text-gray-400 mt-3 text-sm inline-flex gap-2"><span class="text-green-500">+45 %</span>from last month</p>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-green-500 h-8">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941" />
                        </svg>

                    </div>

                </div>
                <div class="bg-white flex flex-col divide-y divide-gray-100 rounded-xl h-32">
                    <div class="flex justify-between items-center p-3">
                        <div class="flex gap-3 items-center">
                            <span class="bg-red-100 rounded-full px-1 py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 text-red-600 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                </svg>

                            </span>
                            <h3>Outcome</h3>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 text-gray-500 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
                        </svg>
                    </div>
                    <div class="flex justify-between p-3 items-center">
                        <div>
                            <h3>KES 45,000</h3>
                            <p class="text-gray-400 mt-3 text-sm inline-flex gap-2"><span class="text-red-500">-12 %</span>from last month</p>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-red-500 h-8">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18L9 11.25l4.306 4.307a11.95 11.95 0 015.814-5.519l2.74-1.22m0 0l-5.94-2.28m5.94 2.28l-2.28 5.941" />
                        </svg>

                    </div>

                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
import Aside from '@/components/Aside.vue';

export default {
    components: {
        Aside
    }
}
</script>

<style>
body,
html {
    background-color: #f5f5f4;
}
</style>
