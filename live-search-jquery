// Implementation of Live Search Bar

function contains(first, second) {
    return first.indexOf(second) != -1);
}

function retrieve() {
    var searchedValue = $('.search-bar').val().toLowerCase();

    $('.divToSearch').each(function() {
        if (contains($(this).find('#childToSearch').text().toLowerCase(), searchedValue)) {
            $(this).show();
        } else {
            $(this).hide();
        }
    });
}
