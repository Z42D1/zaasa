# zaasa// script.js
document.addEventListener('DOMContentLoaded', () => {
    const buttons = document.querySelectorAll('.more-info');

    buttons.forEach(button => {
        button.addEventListener('click', () => {
            const era = button.parentElement.querySelector('h2').textContent;
            alert(`قراءة المزيد عن: ${era}`);
        });
    });
});
