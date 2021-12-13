<script>
  import feather from 'feather-icons'
  export let icon, iconStyle, image, text, url;
</script>

<a class="hover:scale-105 transition-all shadow-md flex items-center p-4 px-6 rounded-full w-full" href={url}>
  {#if icon}
    {@html feather.icons[icon].toSvg({
      class: iconStyle,
    })}
  {/if}
  {#if image}
  <img alt={text} class="w-14 h-14 object-cover" src={image}>
  {/if}
  <span class="ml-4">{text}</span>
</a>