<script>
    export let name;
    export let image;
    export let title;
</script>

<div class="flex flex-col gap-y-1 lg:gap-y-4">
    <img
        src={image}
        alt={name}
        class="w-36 h-36 lg:w-60 lg:h-60 object-cover"
    />
    <div>
        <p class="font-semibold text-sm lg:text-base text-yellow-500">
            {name}
        </p>
        <p class="text-gray-200 text-xs font-bold lg:text-sm">
            {title}
        </p>
    </div>
</div>
