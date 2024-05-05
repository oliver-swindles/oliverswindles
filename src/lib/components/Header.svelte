<script lang="ts">
  import SpaceFrogStudioLogo from "$lib/assets/logos/space-frog-studio.svg";
  import LinkedInLogo from "$lib/assets/logos/linkedin.svg";
</script>

<header class="bg-black fixed left-0 top-0 bottom-0 w-16 flex flex-col justify-end items-center">
  <div class="m font-mono flex flex-col gap-4 absolute leading-4 top-1/2 left-1/2 translate-x-[-50%] translate-y-[-50%] major-mono-display">
    <h2 class="max-w-[2ch] break-words">oliver</h2>
    <h2 class="max-w-[2ch] break-words">swindles</h2>
  </div>
  <menu class="relative p-3 pb-6 flex flex-col gap-4 items-center">
    <a href="https://www.linkedin.com/in/oliver-swindles/"><svg title="LinkedIn" stroke="#FFFFFF" fill="#FFFFFF" stroke-width="0" viewBox="0 0 448 512" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"></path></svg></a>
    <li><a href="https://spacefrogstudio.com"><img src={SpaceFrogStudioLogo} alt="Space Frog Studio Logo" title="Space Frog Studio" width="512" height="512" /></a></li>
  </menu>
</header>
