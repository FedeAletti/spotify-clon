<script lang="ts">
    const currentTime = new Date();
    const hours = currentTime.getHours();

    let greeting = ""

    if (hours < 12) {
        greeting = "Good Morning";
    } else if (hours < 18) {
        greeting = "Good Afternoon";
    } else {
        greeting = "Good Evening";
    }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>