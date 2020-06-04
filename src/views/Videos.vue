<template>
    <div>

    </div>
</template>

<script>
export default {
    name: 'Videos',
    data() {
        return {
            videos: {
                en: [    
                        {
                            title: "Fast and Furious 9 Has Lost Its Mind",
                            id: "m-DsYZpkgQs"
                        },
                        {
                            title: "James Corden: It's Time for Change in the US",
                            id: "qUZIzYwmEDE"
                        },
                        {
                            title: "Wrongly Incarcerated Singer Archie Williams Delivers Unforgettable Song - America's Got Talent 2020",
                            id: "ShgOH1u78XA"
                        }
                    ],
                rs: [
                        {
                            title: "Kako dobiti radnu dozvolu za Ameriku",
                            id: "gzGxuaCwbpI"
                        },
                        {
                            title: "Srpski policajac u Cikagu",
                            id: "p4riZGubkz8"
                        },
                        {
                            title: "Život u Americi",
                            id: "kS2-PoEkq3U"
                        }
                ]
            },
            translations: {
                mainHeading: {
                    en: 'Welcome to Duo Lingual YouTube',
                    rs: 'Dobro dosli na dvojezicni YouTube'
                },
                listOfVideos: {
                    en: 'List of videos',
                    rs: 'Lista klipova'
                }
            }
        }
    }
}
</script>