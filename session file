<?php
// Start the session
session_start();

// If the user is already logged in, redirect the user to the welcome page
if (isset($_SESSION["userid"]) && $_SESSION["userid"] === true) {
    header("Location: welcome.php");
    exit;
}
?>
