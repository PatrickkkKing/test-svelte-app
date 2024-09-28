<script>
    let name = 'Putra';
    import { count } from './store.js';

    function increment() {
        count.update(n => n + 1);
    }
</script>

<h2>Selamat datang di Svelte, {name}!</h2>
<p>Ini adalah komponen Svelte sederhana.</p>

<h2>Jumlah: {$count}</h2>
<button on:click={increment}>Tambah</button>