document.addEventListener('DOMContentLoaded', () => {
    document.querySelectorAll('.sidebar ul li').forEach(item => {
        item.addEventListener('click', () => {
            document.querySelectorAll('.sidebar ul li').forEach(li => li.classList.remove('active'));
            item.classList.add('active');
        });
    });

    document.querySelectorAll('.see-more-btn').forEach(button => {
        button.addEventListener('click', () => {
            alert('See More button clicked');
        });
    });
});
