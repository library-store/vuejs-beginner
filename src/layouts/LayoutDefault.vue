<template>
    <div>
        <header>
            <slot name="header">Base header content</slot>
        </header>
        <main>
            <slot name="main">Base main content</slot>
        </main>
    </div>
</template>

<script>
export default {
    name: 'LayoutDefault'
}
</script>