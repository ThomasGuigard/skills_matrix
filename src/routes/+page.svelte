<script>
    import JobCard from "$lib/components/JobCard.svelte";

    let leadTech = {
        title: "Leader Technique",
        motivations: [
            "Volonté de transmettre ses connaissances",
            "Avoir une vision à plus haut niveau",
            "Travailler sur la conception",
            "Vouloir s'assurer de la qualité optimale du code",
            "Mettre en place des bonnes pratiques",
        ],
        skills: [
            {name: "Savoir synthétiser", type: "Savoir être"},
            {name: "Trouver les bons mots pour corriger quelqu'un", type: "Savoir être"},
            {name: "Principes de Clean Code", type: "Savoir faire"},
            {name: "Connaissance des code smells", type: "Savoir faire"},
            {name: "Maitrise des méthodologies de test", type: "Savoir faire"},
            {name: "Transmettre ses connaissances", type: "Savoir être"},
            {name: "Pratiquer l'egoless programming", type: "Savoir être"},
        ],
        highlights: [
            "Communication",
            "Maitrise du software craftmanship",
            "Méthodologie de conception",
        ],
        downsizes: [
            "Moins de développement",
            "Se rendre disponible pour aider les différents membres de son équipe",
            "Prendre les devants pour valider les besoins",
            "Juste à avoir entre management et non management",
        ],
    };
</script>

<h1>Matrice de competences</h1>


<JobCard job="{leadTech}"/>