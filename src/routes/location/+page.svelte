<script>

    const base_url = "https://rickandmortyapi.com/api";
    const char ="https://rickandmortyapi.com/api/character/1,6";
    const locations ="https://rickandmortyapi.com/api/location/1,6";
    import { page } from '$app/stores';
    const location_id = $page.url.searchParams.get('id');
    console.log(location_id);
    console.log(base_url);
    console.log(char);
    console.log(locations);
    let name;
    let type;
    let dimension;
    let residents = 0;


</script>

<div>
    <h1>Name: { name }</h1>
    <h3>Type: { type } | Dimension: { dimension }</h3>
    <h5>{ residents } residents</h5>
</div>