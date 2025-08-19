if status is-interactive
        pokemon-colorscripts --no-title -n bulbasaur | fastfetch -c $HOME/.config/fastfetch/config-pokemon.jsonc --logo-type file-raw --logo-height 10 --logo-width 5 --logo -
end

function fish_greeting
        echo ""
end
