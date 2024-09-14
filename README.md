# 104neutrinos

Real-time update of statistical measures for neutrino speed records.

Project for semester 1 of the Epitech Math module.

### Description

In the study of neutrinos, a promising particle, researchers need to efficiently store and update particle speed data. Given the number of recorded values, their arithmetic mean, harmonic mean, and standard deviation, this program updates and prints new statistics in real-time.

The program:
1. Takes inputs of the number of values, arithmetic mean, harmonic mean, and standard deviation.
2. Updates and prints the number of values, standard deviation, arithmetic mean, root mean square, and harmonic mean for each new value entered.
3. Continues to update until the keyword "END" is entered.

## Getting Started

### Dependencies

- [Python3](https://python.org/)

### Installation

* Download/Clone the repository and enter its directory.
* Now you are ready to run the code.

## Usage

**Execution:** `./104neutrinos n a h sd`

### Arguments
- **`n`**: Number of recorded values.
- **`a`**: Arithmetic mean of the recorded values.
- **`h`**: Harmonic mean of the recorded values.
- **`sd`**: Standard deviation of the recorded values.

### Examples

To start the program:
```
$> ./104neutrinos 12000 297514 297912 4363
Enter next value: 299042
Number of values: 12001
Standard deviation: 4362.84
Arithmetic mean: 297514.13
Root mean square: 297546.11
Harmonic mean: 297912.09
Enter next value: 302420
Number of values: 12002
Standard deviation: 4362.89
Arithmetic mean: 297514.54
Root mean square: 297546.52
Harmonic mean: 297912.46
Enter next value: END
```

## Acknowledgments

* [Epitech](https://www.epitech.eu/)

## Authors

* **Daniel Sanchez** ([GitHub](https://github.com/angsanch) / [LinkedIn](https://www.linkedin.com/in/angeldanielsanchez/))
* **Raquel Costumero** ([GitHub](https://github.com/raquelcostumerofernandez) / [LinkedIn](https://www.linkedin.com/in/raquel-costumero-fern%C3%A1ndez/))

## License

This project is licensed under the GNU Public License version 3.0 - see the [LICENSE](LICENSE) file for details.
