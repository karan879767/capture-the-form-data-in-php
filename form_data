# capture-the-form-data-in-php
<?php
$requestData = $_POST;

echo "<table>";
foreach ($requestData as $key => $value) {
    echo "<tr><td>$key</td><td>$value</td></tr>";
}
echo "</table>";

echo "<script>";
echo "var requestData = " . json_encode($requestData) . ";";
echo "</script>";
?>
