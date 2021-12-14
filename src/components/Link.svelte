<script>
  import feather from 'feather-icons'
  export let icon, iconStyle, text, url;
</script>

<a class="focus:scale-110 hover:scale-110 transition-all shadow-md flex items-center p-4 px-6 rounded-md w-full flex items-center space-x-4" href={url}>
  {#if icon}
    {@html feather.icons[icon].toSvg({
      class: [iconStyle, "justify-center items-center"].join(" "),
    })}
  {/if}
  <span class="flex-1">{text}</span>
</a>