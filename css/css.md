# CSS i denna mapp

{
    --red: #E74C3C;
    --brown: #5E574D;
    --tan: #E2C290;
    --green:#519E8A;
    --besie:#FFF8D1;
}
 
 wrapper{}

    display: grid;
    grid-template-columns: 15% 1fr 15%;
    grid-template-rows: 100px 300px 200px 300px 150px;
    grid-template-areas:
        'hd hd hd'
        'na na na'
        'se se se'
        'ar ar as'
        'ft ft ft'
 }