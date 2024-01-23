function validateForm(formId) {
    var form = document.getElementById(formId);

    // Simple form validation
    var loginInput = form.querySelector('[name="login"]');
    var passwordInput = form.querySelector('[name="password"]');

    if (loginInput.value.trim() === '') {
        alert('Please enter a login.');
        return false;
    }

    if (passwordInput.value.trim() === '') {
        alert('Please enter a password.');
        return false;
    }

    // If the validation passes, the form will be submitted
    return true;
}
