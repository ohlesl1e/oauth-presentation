<div flex flex-col items-center h-screen>
    <div class="b-2 border-gray rounded-3 my-auto" style='width: 928px'>
        <div bg-gray-300 rounded-t-3 py-3 px-3>
            <div i-mdi-circle text-4xl text-red />
            <div i-mdi-circle text-4xl text-amber />
            <div i-mdi-circle text-4xl text-green />
            <div
                class="flex flex-row bg-white rounded-3 border-gray b-2 text-2xl mt-3 text-center py-1"
            >
                <span class="text-green-700 w-4/24">
                    <div i-mdi-lock ml-3 mr-3 mb-1 />
                    Secure
                </span>
                <span class="w-1/24 font-light">|</span>
                <span class="w-19/24 font-light"
                    >https://account.google.com/oauth/authorize?response_type=cod</span
                >
            </div>
        </div>
        <div flex flex-col items-center>
            <div flex flex-row mt-8 items-center>
                <div class="i-mdi-account-circle text-blue-500 text-7xl" />
                <div class="i-logos-google-drive text-6xl" />
            </div>
            <div text-xl mt-8 class='tooltip'>
                <div class="i-mdi-triangle-small-down" />
                Google Docs would like to:
                <span class="tooltiptext ">
                    <div text-l mb-2>Developer info</div>
                    <div text-sm>email: eugene.pupov@gmail.com</div>
                    <div text-sm>
                        Clicking "Allow" will redirect you to:
                        https://googledocs.docscloud.info/g.php
                    </div>
                </span>
            </div>
            <div
                class="flex w-5/10 items-center mt-8 border-b-1 border-t-1 border-gray-400 py-5"
            >
                <div class="w-2/24 i-logos-google-gmail text-xl" />
                <h2 class="w-20/24">
                    Read, send, delete, and manage your email
                </h2>
                <div
                    class="i-mdi-information-outline w-2/24 text-xl text-gray"
                />
            </div>

            <div
                class="flex w-5/10 items-center border-b-1 border-gray-400 py-5"
            >
                <div class="w-2/24 i-mdi-contacts text-2xl text-blue-500" />
                <h2 class="w-20/24">Manage your contacts</h2>
                <div
                    class="i-mdi-information-outline w-2/24 text-xl text-gray"
                />
            </div>
            <div class="w-5/10 mt-8">
                <small>
                    By clicking Allow, you allow this app and Google to use your
                    information in accordance with their respective <a
                        href="/"
                        text-blue-600>Terms of service</a
                    >
                    and <a href="/" text-blue-600>privacy policies</a>. You can
                    change this and other
                    <a href="/" text-blue-600>Account Permissions</a> at any time.
                </small>
            </div>
        </div>
        <div class="flex flex-row justify-end mx-auto my-8 w-5/10">
            <button
                class="me-3 px-5 py-1 bg-gray-100 border border-1 border-gray200 rounded"
                >Deny</button
            >
            <button
                class="px-5 py-1 bg-blue-500 border border-1 border-blue-700 rounded text-white"
                >Allow</button
            >
        </div>
    </div>
</div>

<style>
    .tooltip {
        position: relative;
        display: inline-block;
    }

    .tooltip .tooltiptext {
        visibility: hidden;
        width: 300px;
        background-color: #555;
        color: #fff;
        text-align: left;
        border-radius: 6px;
        padding: 0.5rem;
        position: absolute;
        z-index: 1;
        bottom: -400%;
        left: 20%;
        margin-left: -60px;
        opacity: 0;
        transition: opacity 0.3s;
    }

    .tooltip .tooltiptext::after {
        content: "";
        position: absolute;
        bottom: 100%;
        left: 50%;
        margin-left: -5px;
        border-width: 5px;
        border-style: solid;
        border-color: transparent transparent #555 transparent;
    }

    .tooltip:hover .tooltiptext {
        visibility: visible;
        opacity: 1;
    }
</style>
