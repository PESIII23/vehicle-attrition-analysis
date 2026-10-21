# vehicle-attrition-analysis
Analyzing and predicting vehicle attrition patterns to generate insights for vehicle intelligence, market analysis, and emerging collector vehicles.

# vehicle-attrition-analysis
Analyzing and predicting vehicle attrition patterns to generate insights for vehicle intelligence, market analysis, and emerging collector vehicles.

---

## Setup

The notebook reads from Hagerty's Snowflake, so running it requires Snowflake access. Data is never committed to this repo, and notebook outputs are stripped on commit.

```bash
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/nbstripout --install --attributes .gitattributes
```

Add a connection named `vehicle_attrition` to `~/.snowflake/connections.toml`:

```toml
[vehicle_attrition]
account = "<account_identifier>"
user = "<your_email>"
authenticator = "externalbrowser"
warehouse = "<warehouse>"
database = "WORKSPACE"
schema = "ENGINEER"
role = "<role>"
```

Then open `notebooks/VIO_Project.ipynb` and select the `.venv` interpreter.

---

## LinkedIn

- [Intro](https://www.linkedin.com/feed/update/urn:li:activity:7508624093123108864/)
- [Mid-Semester]()
- [Final]()

---

## Support

If you run into any issues or have questions:
- Email: [pesmithiii7@gmail.com](mailto:pesmithiii7@gmail.com)
- Documentation: [Milestone 1](https://docs.google.com/document/d/1CRQ4GBznRPawZAWiKM7B54HechiEnJUlPyMthUrnDMA/edit?usp=sharing)
