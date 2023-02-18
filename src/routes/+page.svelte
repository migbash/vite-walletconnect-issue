<script lang="ts">
  import { getMoralisAuth } from "@moralisweb3/client-firebase-auth-utils";
  import { signInWithMoralis } from "@moralisweb3/client-firebase-evm-auth";

  // FIXME: toggle / (comment/uncomment) these two packages below:
  // NOTE: to remove the target `dev` error of buffer issue.
  import { Web3Provider } from "@ethersproject/providers";
  import WalletConnectProvider from "@walletconnect/web3-provider";
  // CAUSE THE ERROR, just simply by their importing...
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
