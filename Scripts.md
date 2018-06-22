For Trello list colors <a href="https://trello.com/c/RbVustT9/75-change-list-colors-likely-to-be-implemented-as-a-border-trying-not-to-mess-up-the-ui">(link to Trello resource)

<pre>$('.list').each(function(i, el) {
    switch ($(el).find("h2").text()) {
        case "Doing":
            $(el).css("background-color", "orange");
            break;
        default:
            $(el).css("background-color", "green");
    }
    });</pre>
