# Navigation

<chart-demo data="2" v-bind:config="{
        type: 'bar',
        height: 140,
		isNavigable: 1,
        colors: ['orange'],
        axisOptions: { xAxisMode: 'tick' },
        barOptions: { spaceRatio: 0.2 },
    }">
</chart-demo>


<chart-demo data="2" sideContent="2"
	v-bind:config="{
        type: 'bar',
        height: 140,
		isNavigable: 1,
        colors: ['grey'],
        axisOptions: { xAxisMode: 'tick' },
        barOptions: { spaceRatio: 0.2 },
    }">
</chart-demo>