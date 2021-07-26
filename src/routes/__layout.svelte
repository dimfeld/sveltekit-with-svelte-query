<script>
  import { QueryClient, QueryClientProvider } from '@sveltestack/svelte-query';

  const client = new QueryClient();
</script>

<QueryClientProvider {client}>
  <slot />
</QueryClientProvider>
