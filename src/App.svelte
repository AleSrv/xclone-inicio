<script>
    import Icon from "./components/Icon.svelte";
    import { icons } from "./lib/info.js";
</script>

<style>
    .container {
        padding-left: 3rem;
        padding-right: 3rem;
    }
    
    .logo {
        padding-top: 1.5rem;
        padding-bottom: 1.5rem;
    }
    
    .grid-container {
        width: 100%;
        display: grid;
        grid-template-columns: 1fr 2fr 1fr; /* Ajuste para tener más espacio en la columna principal */
    }
    
    .main {
        grid-column: 1; /* Columna principal a la izquierda */
    }
    
    .spacer {
        grid-column: 2; /* Espacio vacío en el centro */
        padding-left: 0.5rem;
        padding-right: 0.5rem;
        font-size: 2.5rem;
        color: white;
    }
    
    .aside {
        grid-column: 3; /* Columna de aside a la derecha */
        padding-left: 0.5rem; /* px-2 */
        padding-right: 0.5rem;
        padding-bottom: 2.5rem; /* pb-10 */
    }
    
    .aside h2 {
        font-size: 1.875rem; /* text-3xl */
        font-weight: bold; /* font-bold */
    }
    
    .aside .trends-header {
        padding-top: 2.5rem; /* pt-10 */
        padding-bottom: 1.25rem; /* pb-5 */
    }
    
    .link {
        color: #3b82f6; /* text-blue-500 */
    }
    
    .icon-button {
        display: flex;
        align-items: center; /* items-center */
        margin-left: 1.25rem; /* ml-5 */
        margin-top: 0.75rem; /* mt-3 */
        padding-top: 0.5rem; /* py-2 */
        padding-bottom: 0.5rem;
        padding-left: 5rem; /* px-20 */
        padding-right: 5rem;
        font-size: 1.25rem; /* text-xl */
        border-radius: 9999px; /* rounded-full */
        background-color: #3b82f6; /* bg-blue-500 */
        color: white; /* text-white */
    }
    
    </style>