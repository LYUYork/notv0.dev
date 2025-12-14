https://supabase.com/docs/guides/local-development?queryGroups=package-manager&package-manager=npm

mkdir -p data && cd data
sudo pnpm add supabase --save-dev --allow-build=supabase

pnpx supabase start

pnpx supabase status -o env