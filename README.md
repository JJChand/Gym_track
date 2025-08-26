# Gym Workout Tracker

A comprehensive Excel-based workout tracking system with a calendar-like format for monitoring your gym progress.

## Features

- **Calendar View**: Monthly layout showing all dates with workout tracking
- **Comprehensive Tracking**: Date, training part, exercise, sets, reps, weight, rest time, and notes
- **Multiple Sheets**: 
  - Workout Tracker (main calendar view)
  - Summary (monthly progress overview)
  - Template (common exercises reference)
- **Professional Formatting**: Clean, easy-to-read design with proper styling

## Setup Instructions

1. **Install Python dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the script**:
   ```bash
   python create_gym_tracker.py
   ```

3. **Open the generated Excel file**: `gym_workout_tracker.xlsx`

## How to Use

### Main Workout Tracker Sheet
- **Date & Day**: Automatically populated for the current month
- **Training Part**: Enter the muscle group (e.g., Chest, Back, Legs, Shoulders, Arms, Core)
- **Exercise**: Specific exercise name (e.g., Bench Press, Squats, Pull-ups)
- **Sets**: Number of sets performed
- **Reps**: Number of repetitions per set
- **Weight**: Enter weight in pounds or kilograms
- **Rest Time**: Rest period between sets
- **Notes**: Additional comments, form notes, or observations

### Summary Sheet
Track your monthly progress including:
- Total workouts completed
- Most trained muscle group
- Total sets and reps
- Average weight used
- Progress notes

### Template Sheet
Reference sheet with common exercises and recommended:
- Set ranges
- Rep ranges
- Rest periods

## Customization

You can modify the script to:
- Change the month/year displayed
- Add more exercises to the template
- Modify column headers or formatting
- Add additional tracking metrics

## Tips for Effective Tracking

1. **Be Consistent**: Record your workouts immediately after completion
2. **Track Progress**: Monitor weight increases and rep improvements
3. **Use Notes**: Record form cues, how you felt, or any issues
4. **Regular Review**: Check your summary sheet monthly to assess progress
5. **Set Goals**: Use the tracker to set and achieve specific fitness goals

## File Structure

- `create_gym_tracker.py` - Python script to generate the Excel file
- `requirements.txt` - Python package dependencies
- `gym_workout_tracker.xlsx` - Generated workout tracker (after running the script)
- `README.md` - This instruction file

## Requirements

- Python 3.7 or higher
- openpyxl library
- pandas library

The generated Excel file will work with Microsoft Excel, Google Sheets, LibreOffice Calc, and other spreadsheet applications.
# Gym_track
# Gym_track
