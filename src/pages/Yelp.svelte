<div class="flex flex-wrap mx-auto w-14/24 text-left h-screen">
    <div class="my-auto ">
        <h1
            class="font-sans font-black text-red-700 text-2xl text-left tracking-tight"
        >
            Are your friends already on Yelp?
        </h1>
        <p class="mt2">
            Many of your friends may already be here, now you can find out. Just
            log in and we'll display all your contacts, and you can select which
            ones to invite! And don't worry, we don't keep your email password
            or your friends' addresses. Wd loathe spam, too.
        </p>
        <form>
            <div class="flex items-baseline mt-3">
                <label class="text-xl w-1/4" for="service"
                    >Your Email Service</label
                >
                <span class="w-3/4 px-2 items-baseline flex">
                    <span class="w-1/6 text-3xl">
                        <input type="radio" name="service" /><span
                            class="i-vscode-icons-file-type-outlook ml-3"
                        />
                    </span>
                    <span class="w-1/6 text-3xl">
                        <input type="radio" name="service" /><span
                            class="i-ps-yahoo ml-3 text-red-600"
                        />
                    </span>
                    <span class="w-1/6 text-3xl">
                        <input type="radio" name="service" /><span
                            class="i-simple-icons-aol ml-3 text-blue-gray-900"
                        />
                    </span>
                    <span class="w-1/6 text-3xl">
                        <input type="radio" name="service" /><span
                            class="i-logos-google-gmail ml-3"
                        />
                    </span>
                </span>
            </div>
            <div class="flex items-baseline mt-3">
                <label class="text-xl w-1/4" for="email"
                    >Your Email Address</label
                >
                <span class="w-3/4 px-2 items-baseline">
                    <input type="email" class="b rounded" />
                    <small class="italic text-truegray-5"
                        >(e.g. bob@gmail.com)</small
                    >
                </span>
            </div>
            <div class="flex items-baseline mt-3">
                <label class="text-xl w-1/4" for="password"
                    >Your Email Password</label
                >
                <span class="w-3/4 px-2 items-baseline">
                    <input type="password" class="b rounded" />
                    <small class="italic text-truegray-5"
                        >(The password you use to log into your Gmail email)</small
                    >
                </span>
            </div>
            <div class="text-center mt-8">
                <a href="/" class="text-blue">Skip this step</a>
                <button class='ml-3 b rounded px-5 bg-amber-200 drop-shadow'>
                    <strong class='text-red-700'>Check Contacts</strong>
                </button>
            </div>
        </form>
    </div>
</div>
