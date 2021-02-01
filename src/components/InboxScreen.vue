<!-- src/components/InboxScreen.vue -->

<template>
	<PureInboxScreen :error="false" />
</template>

<script>
import PureInboxScreen from './PureInboxScreen';

export default {
	name: 'InboxScreen',
	components: { PureInboxScreen },
};
</script>
