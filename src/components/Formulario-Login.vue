<template>
    <section class="flex flex-col rounded-md px-36 py-14">
        <div class="logo">
            <img src="https://portalsuperingresso.s3.amazonaws.com/eleventickets180x127.png" alt="Logo" class="w-36 pb-10">
        </div>
        <form  class="space-y-12 ">
			<div class="space-y-4">
                <div>
					<label for="id" class="block mb-2 text-sm">Id do projeto</label>
					<input type="text" name="id" id="id" class="w-full px-3 py-2 rounded-md ">

				</div>
				<div>
					<label for="email" class="block mb-2 text-sm">E-mail</label>
					<input type="email" name="email" id="email" class="w-full px-3 py-2 rounded-md ">
				</div>
				<div>
					<label for="password" class="text-sm">Senha</label>
					<input type="password" name="password" id="password" class="w-full px-3 py-2  rounded-md ">
				</div>
			</div>
			<div class="space-y-2">
			    <button type="button" class="px-7 py-2 rounded-md" @click="this.$router.push('/painel')">Login</button>
			</div>
		</form>
        <p class="pt-10">Powered by Imply Group - Painel administrativo de projetos criado pelo grupo. Caso você não tenha acesso por favor contatar o SAC solicitando o acesso ao painel.</p>
    </section>
</template>

<script>
    export default {
        name: "Formulario-Login",
    }
</script>

<style  scoped>
    input {
        border: 1px solid #b3b3b3;
        background-color: #f3f2f2;
    }

    button {
        background-color: #FF6400;
    }
    p {
        color: #808080;
        font-size: 14px;
    }
    label {
        color: #808080;
    }

    .logo {
        display: flex;
        justify-content: center;
    }
</style>