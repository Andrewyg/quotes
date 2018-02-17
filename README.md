<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script>
 $(document).bind('scroll',function(e){
    $('h1').each(function(){
        if (
           $(this).offset().top < window.pageYOffset + 10
//begins before top
        && $(this).offset().top + $(this).height() > window.pageYOffset + 10
//but ends in visible area
//+ 10 allows you to change hash before it hits the top border
        ) {
            window.location.hash = $(this).attr('id');
        }
    });
});
<script>


# List of contents
- [Welcome](#welcome)

---

# Welcome

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sapien nibh, laoreet id iaculis nec, ornare id turpis. Pellentesque libero turpis, posuere vitae ultricies a, scelerisque bibendum odio. Etiam non enim nibh. Curabitur non urna varius, commodo purus sit amet, mattis purus. Curabitur sit amet lacus et quam vulputate scelerisque. Suspendisse at accumsan ligula, at varius dolor. Proin a lobortis tortor, nec tristique mauris. Quisque eget quam et lorem vehicula dignissim. In varius arcu lorem, vitae aliquam velit ullamcorper ac. Sed rutrum, orci non bibendum venenatis, ipsum eros interdum ligula, et consectetur diam purus non dui. Phasellus ex orci, accumsan vel orci a, semper varius lacus.

Interdum et malesuada fames ac ante ipsum primis in faucibus. Proin ut tincidunt erat. Nulla facilisi. Suspendisse posuere convallis mauris, ac aliquam ante viverra quis. Etiam feugiat ante arcu, sit amet luctus mi porta non. Curabitur dictum semper est eu feugiat. Fusce iaculis semper est, non feugiat nisl accumsan nec. Suspendisse scelerisque eros ut commodo sollicitudin. Nam hendrerit tortor non eros sollicitudin vestibulum. Aenean ac tellus vitae mi viverra venenatis non ut urna. Ut et vulputate odio. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Sed ullamcorper ullamcorper vulputate.

Nunc et elit condimentum, egestas massa quis, imperdiet neque. Donec tellus nisl, porttitor id dui ac, accumsan molestie sem. Aenean molestie fermentum erat, nec molestie massa finibus dictum. Curabitur in eros pulvinar, aliquam felis ac, fermentum diam. Pellentesque viverra velit ut ipsum rhoncus finibus eget vel enim. Vestibulum venenatis mollis faucibus. Suspendisse potenti. Proin eget augue enim. Nulla sodales massa nec diam mollis consequat.

---

# Wel2

> Aenean cursus urna justo, eget vehicula nisi dictum nec. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vivamus pulvinar magna nec velit sodales, id rutrum erat pretium. Duis efficitur nulla in augue mattis aliquam id eget massa. Quisque pellentesque accumsan mattis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Ut ultrices, purus quis viverra feugiat, orci arcu volutpat arcu, eu feugiat justo nisl non dui. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Praesent at lectus non neque laoreet condimentum.
> 
> Donec elementum, urna eu dictum molestie, enim urna pharetra tortor, ullamcorper sodales urna diam ac risus. Quisque eu tellus eu felis bibendum maximus id ac eros. Ut vel elit laoreet lectus posuere iaculis vitae ut magna. Nam fermentum pretium sagittis. Etiam vestibulum aliquam lorem, non imperdiet ipsum venenatis eget. Praesent convallis pulvinar nibh quis commodo. Praesent erat eros, vulputate sed est in, interdum tincidunt metus. Nam sem lectus, tempor non turpis non, tempor tincidunt nisi. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
> 
> Nullam vehicula efficitur rhoncus. Pellentesque turpis mi, venenatis non diam quis, dapibus sollicitudin urna. Donec hendrerit luctus ante eu interdum. Cras sodales lobortis ipsum, in ultricies eros rhoncus ut. Cras convallis quam vitae justo scelerisque mattis. In scelerisque maximus nibh, in commodo sapien sodales id. Etiam vel lorem sed libero ullamcorper dignissim.
