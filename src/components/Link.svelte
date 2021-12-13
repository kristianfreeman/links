<script>
  import feather from 'feather-icons'
  export let icon, iconStyle, text, url;
</script>

<a class="focus:scale-110 hover:scale-110 transition-all shadow-md flex items-center p-4 px-6 rounded-full w-full" href={url}>
  {#if icon}
    {@html feather.icons[icon].toSvg({
      class: iconStyle,
    })}
  {/if}
  <span class="ml-4">{text}</span>
</a>