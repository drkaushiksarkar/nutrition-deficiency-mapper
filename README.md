# Nutrition Deficiency Mapper

Nutritional deficiency mapping platform for intervention targeting using DHS, MICS, and WASH survey data with equity-focused analysis.

## Architecture

```
nutrition-deficiency-mapper/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **survey_processor**: Core survey processor functionality
- **prevalence_estimator**: Core prevalence estimator functionality
- **intervention_targeter**: Core intervention targeter functionality
- **equity_analyzer**: Core equity analyzer functionality
- **trend_monitor**: Core trend monitor functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m nutrition_deficiency_mapper.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
