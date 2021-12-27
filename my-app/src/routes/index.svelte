<script>
    import TodoItem from "$lib/todo-items.svelte";

    const title = "Todo App"
</script>

<h1> {title} </h1>

<form action="" method="">
    <input type="text" name="text" aria-label="Add a todo" placeholder="+ type to add a todo">

</form>

<TodoItem/>