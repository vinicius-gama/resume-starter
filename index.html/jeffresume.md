.resume {
    display: grid;
    width  : 200mm;
    height: 340mm;
    grid-template-columns: 1fr 2fr;
    grid-template-rows   : 1fr 1fr 1fr 1fr;
    box-shadow           : 0 5px 9px 0 rgba(0, 0, 0, 0.35);
    grid-template-areas  :
        "photo education"
        "name work"
        "about work"
        "skills community";
}
.grid-area {
    padding: 1em 1em 1em 1em;
    border : 1px black solid;
}

.name {
    grid-area: name;
    background-color: lightgray;
    text-align: center;
}

.photo {
    grid-area       : photo;
    background-color:orange;
    
}

.about {
    grid-area       : about;
    background-color: lightgray;
}

.work {
    grid-area: work;
}

.skills {
    grid-area       : skills;
    background-color: lightgray;
}

.education {
    grid-area       : education;
}

.community {
    grid-area: community;
}

h2 {
text-align: center;

}


