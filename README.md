# TMDB
Tmdb Movie TV 
Wrapper in PHP for The Movie Data Base version 3



### Initialize the class ###

    <?php
        include('TMDb.php');

        // Default English language
        $tmdb = new TMDb('API-key');

        // Set-up the class with your own language
        $tmdb_nl = new TMDb('API-key', 'nl');

        // If you want to load the TMDb-config (default FALSE)
        $tmdb_load_config = new TMDb('API-key', 'en', TRUE);
	?>
