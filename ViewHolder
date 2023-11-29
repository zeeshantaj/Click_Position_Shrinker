//viewHolder 

   holder.itemView.setOnTouchListener((view, motionEvent) -> {
            switch (motionEvent.getAction()) {
                case MotionEvent.ACTION_DOWN:
                    // Scale down the clicked item
                    view.setScaleX(0.9f);
                    view.setScaleY(0.9f);
                    break;
                case MotionEvent.ACTION_UP:
                case MotionEvent.ACTION_CANCEL:
                    // Restore the original size when touch is released or canceled
                    view.setScaleX(1.0f);
                    view.setScaleY(1.0f);
                    break;
            }
            return false;
        });
