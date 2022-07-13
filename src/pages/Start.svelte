<script>
    let responseType = "code";
    let scope = "contacts.readonly";
</script>

<div class="flex flex-col items-center h-screen">
    <div
        class="flex flex-wrap font-sans my-auto text-neutral-900 text-5xl w-10/12"
    >
        https://accounts.google.com/o/oauth2/v2/auth/oauthchooseaccount?<span
            text-red-700>redirect_uri</span
        >=https://yelp.com/callback&<span text-red-700>response_type</span
        >=<span text-green-600 on:click={(e) => (responseType = "token")}
            >{responseType}</span
        >&<span text-red-700>client_id</span>=407408718192&<span text-red-700
            >scope</span
        >=<span
            text-green-600
            on:click={(e) => (scope = "openid+userinfo.profile")}>{scope}</span
        >&state=&#123;csrf_token&#125;
    </div>
</div>
