

# All entries with the tag: <tag id="tag">a</tag>
!{blogList}

<script>
  const params = new Proxy(new URLSearchParams(window.location.search), {
    get: (searchParams, prop) => searchParams.get(prop),
  })
  document.getElementById('tag').innerText = params.tag
  new Array(...document.querySelectorAll(`.card:not(.${params.tag})`)).forEach(itm =>{
    itm.style.display = 'none'
  })
</script>
