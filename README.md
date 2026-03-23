# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-23 05:51:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 117906.6 (32h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4195376
telemt_connections_bad_total 398509
telemt_connections_current 1448
telemt_connections_me_current 1448
telemt_handshake_timeouts_total 140472
telemt_upstream_connect_attempt_total 43830
telemt_upstream_connect_success_total 43829
telemt_upstream_connect_attempts_per_request{bucket="1"} 43829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1542
telemt_me_reconnect_success_total 687
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_route_drop_no_conn_total 3441877
telemt_me_route_drop_channel_closed_total 1336
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3434426
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 921
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 14178
telemt_desync_full_logged_total 4510
telemt_desync_suppressed_total 9668
telemt_desync_frames_bucket_total{bucket="1_2"} 3667
telemt_desync_frames_bucket_total{bucket="3_10"} 5282
telemt_desync_frames_bucket_total{bucket="gt_10"} 5229
telemt_pool_swap_total 130
telemt_pool_force_close_total 3976
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 758
telemt_me_draining_writers_reap_progress_total 40152
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2875
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36176
telemt_me_writer_teardown_success_total{mode="normal"} 40435
telemt_me_writer_teardown_noop_total 40165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 435.612802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 758
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 616
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 3421820
telemt_user_connections_current{user="hello"} 1448
telemt_user_octets_from_client{user="hello"} 45770833820 (42.63 GB)
telemt_user_octets_to_client{user="hello"} 898494141756 (836.79 GB)
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 131273.0 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4171659
telemt_connections_bad_total 387313
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 108999
telemt_upstream_connect_attempt_total 81822
telemt_upstream_connect_success_total 80840
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 81710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11019
telemt_me_reconnect_success_total 3965
telemt_me_reader_eof_total 3936
telemt_me_idle_close_by_peer_total 3935
telemt_me_route_drop_no_conn_total 3675575
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3308240
telemt_me_endpoint_quarantine_total 1065
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1033
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 90
telemt_desync_total 13603
telemt_desync_full_logged_total 7674
telemt_desync_suppressed_total 5929
telemt_desync_frames_bucket_total{bucket="1_2"} 3093
telemt_desync_frames_bucket_total{bucket="3_10"} 5336
telemt_desync_frames_bucket_total{bucket="gt_10"} 5174
telemt_pool_swap_total 123
telemt_pool_force_close_total 3417
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 55102
telemt_me_writer_removed_unexpected_total 3858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6958
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52045
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2932
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51685
telemt_me_writer_teardown_success_total{mode="normal"} 59003
telemt_me_writer_teardown_noop_total 55103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.964500
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 279
telemt_me_writer_restored_same_endpoint_total 3512
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 3322669
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 44697514543 (41.63 GB)
telemt_user_octets_to_client{user="hello"} 839868341849 (782.19 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 206132.8 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16711613
telemt_connections_bad_total 1691609
telemt_connections_current 1827
telemt_connections_me_current 1827
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 409540
telemt_upstream_connect_attempt_total 92474
telemt_upstream_connect_success_total 92363
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1733
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3269
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1656
telemt_me_idle_close_by_peer_total 1653
telemt_me_route_drop_no_conn_total 14128071
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13277843
telemt_me_endpoint_quarantine_total 1396
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1561
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 7
telemt_desync_total 55424
telemt_desync_full_logged_total 17719
telemt_desync_suppressed_total 37705
telemt_desync_frames_bucket_total{bucket="1_2"} 12359
telemt_desync_frames_bucket_total{bucket="3_10"} 21714
telemt_desync_frames_bucket_total{bucket="gt_10"} 21351
telemt_pool_swap_total 223
telemt_pool_force_close_total 7150
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1106
telemt_me_draining_writers_reap_progress_total 71235
telemt_me_writer_removed_unexpected_total 1589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66141
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64085
telemt_me_writer_teardown_success_total{mode="normal"} 72110
telemt_me_writer_teardown_noop_total 71289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.333342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1106
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13277645
telemt_user_connections_current{user="hello"} 1827
telemt_user_octets_from_client{user="hello"} 201011604285 (187.21 GB)
telemt_user_octets_to_client{user="hello"} 3611496837899 (3.28 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 206137.4 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12206753
telemt_connections_bad_total 1295212
telemt_connections_current 1058
telemt_connections_me_current 1058
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 354003
telemt_upstream_connect_attempt_total 106964
telemt_upstream_connect_success_total 105550
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 106450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4721
telemt_me_reconnect_success_total 2031
telemt_me_reader_eof_total 1895
telemt_me_idle_close_by_peer_total 1895
telemt_me_route_drop_no_conn_total 4617997
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9028006
telemt_me_endpoint_quarantine_total 1404
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1576
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 6
telemt_desync_total 39713
telemt_desync_full_logged_total 13414
telemt_desync_suppressed_total 26299
telemt_desync_frames_bucket_total{bucket="1_2"} 9851
telemt_desync_frames_bucket_total{bucket="3_10"} 15247
telemt_desync_frames_bucket_total{bucket="gt_10"} 14615
telemt_pool_swap_total 220
telemt_pool_force_close_total 6493
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 69416
telemt_me_writer_removed_unexpected_total 1925
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5981
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62923
telemt_me_writer_teardown_success_total{mode="normal"} 71204
telemt_me_writer_teardown_noop_total 69441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140645
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.718000
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140645
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1736
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8965541
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 220654151692 (205.50 GB)
telemt_user_octets_to_client{user="hello"} 4039048463159 (3.67 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 206098.3 (57h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11357518
telemt_connections_bad_total 1043388
telemt_connections_current 1108
telemt_connections_me_current 1108
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 359965
telemt_upstream_connect_attempt_total 91337
telemt_upstream_connect_success_total 89759
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5918
telemt_me_reconnect_success_total 2498
telemt_me_reader_eof_total 2240
telemt_me_idle_close_by_peer_total 2239
telemt_me_route_drop_no_conn_total 5387128
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8536468
telemt_me_endpoint_quarantine_total 1454
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1540
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 38845
telemt_desync_full_logged_total 12899
telemt_desync_suppressed_total 25946
telemt_desync_frames_bucket_total{bucket="1_2"} 9801
telemt_desync_frames_bucket_total{bucket="3_10"} 14878
telemt_desync_frames_bucket_total{bucket="gt_10"} 14166
telemt_pool_swap_total 216
telemt_pool_force_close_total 6381
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 763
telemt_me_draining_writers_reap_progress_total 69993
telemt_me_writer_removed_unexpected_total 2385
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5807
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63612
telemt_me_writer_teardown_success_total{mode="normal"} 72315
telemt_me_writer_teardown_noop_total 70064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142379
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.981477
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142379
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 763
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2174
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8528229
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 194430746439 (181.08 GB)
telemt_user_octets_to_client{user="hello"} 3536641828133 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 76378.3 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11738872
telemt_connections_bad_total 711021
telemt_connections_current 2114
telemt_connections_me_current 2114
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 323264
telemt_upstream_connect_attempt_total 68002
telemt_upstream_connect_success_total 64409
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 66728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2319
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8468
telemt_me_reconnect_success_total 1582
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1000
telemt_me_route_drop_no_conn_total 25393884
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9696847
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 613
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 17442
telemt_desync_full_logged_total 4893
telemt_desync_suppressed_total 12549
telemt_desync_frames_bucket_total{bucket="1_2"} 3375
telemt_desync_frames_bucket_total{bucket="3_10"} 7144
telemt_desync_frames_bucket_total{bucket="gt_10"} 6923
telemt_pool_swap_total 78
telemt_pool_force_close_total 2443
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 533
telemt_me_draining_writers_reap_progress_total 25321
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23463
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22878
telemt_me_writer_teardown_success_total{mode="normal"} 26731
telemt_me_writer_teardown_noop_total 25340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.155602
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 533
telemt_me_refill_failed_total 350
telemt_me_writer_restored_same_endpoint_total 1013
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 9724355
telemt_user_connections_current{user="hello"} 2114
telemt_user_octets_from_client{user="hello"} 91377182783 (85.10 GB)
telemt_user_octets_to_client{user="hello"} 744204351273 (693.09 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 738
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 206104.9 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11331656
telemt_connections_bad_total 997022
telemt_connections_current 1324
telemt_connections_me_current 1324
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 256530
telemt_upstream_connect_attempt_total 120341
telemt_upstream_connect_success_total 119078
telemt_upstream_connect_fail_total 1086
telemt_upstream_connect_attempts_per_request{bucket="1"} 120164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1086
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73589
telemt_me_reconnect_success_total 3286
telemt_me_reader_eof_total 2970
telemt_me_idle_close_by_peer_total 2967
telemt_me_route_drop_no_conn_total 5332015
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8919559
telemt_me_endpoint_quarantine_total 1400
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 47
telemt_me_single_endpoint_outage_reconnect_success_total 45
telemt_me_single_endpoint_quarantine_bypass_total 47
telemt_me_single_endpoint_shadow_rotate_total 1566
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 51
telemt_desync_total 47488
telemt_desync_full_logged_total 16336
telemt_desync_suppressed_total 31152
telemt_desync_frames_bucket_total{bucket="1_2"} 9658
telemt_desync_frames_bucket_total{bucket="3_10"} 18206
telemt_desync_frames_bucket_total{bucket="gt_10"} 19624
telemt_pool_swap_total 212
telemt_pool_force_close_total 6096
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 74120
telemt_me_writer_removed_unexpected_total 2987
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68024
telemt_me_writer_teardown_success_total{mode="normal"} 77154
telemt_me_writer_teardown_noop_total 74121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151275
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.389878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151275
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 4323
telemt_me_writer_restored_same_endpoint_total 2763
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7371
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8922150
telemt_user_connections_current{user="hello"} 1324
telemt_user_octets_from_client{user="hello"} 199527566101 (185.82 GB)
telemt_user_octets_to_client{user="hello"} 3416205553768 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 142941.2 (39h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12127049
telemt_connections_bad_total 494356
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4893509
telemt_upstream_connect_attempt_total 69287
telemt_upstream_connect_success_total 68797
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 69274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_reconnect_attempts_total 49393
telemt_me_reconnect_success_total 1979
telemt_me_reader_eof_total 1665
telemt_me_idle_close_by_peer_total 1664
telemt_me_route_drop_no_conn_total 4152859
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5827289
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1104
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32785
telemt_desync_full_logged_total 11227
telemt_desync_suppressed_total 21558
telemt_desync_frames_bucket_total{bucket="1_2"} 6598
telemt_desync_frames_bucket_total{bucket="3_10"} 12900
telemt_desync_frames_bucket_total{bucket="gt_10"} 13287
telemt_pool_swap_total 152
telemt_pool_force_close_total 4289
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 54042
telemt_me_writer_removed_unexpected_total 1702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4270
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51532
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49753
telemt_me_writer_teardown_success_total{mode="normal"} 55802
telemt_me_writer_teardown_noop_total 54049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109851
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.875723
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109851
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 2754
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5819155
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 122082801712 (113.70 GB)
telemt_user_octets_to_client{user="hello"} 2267844813858 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 123912.1 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1723807
telemt_connections_bad_total 37654
telemt_connections_current 785
telemt_connections_me_current 785
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37822
telemt_upstream_connect_attempt_total 58267
telemt_upstream_connect_success_total 58071
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 58228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 853
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2520
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 582429
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1530827
telemt_me_endpoint_quarantine_total 1054
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1022
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10515
telemt_desync_full_logged_total 2968
telemt_desync_suppressed_total 7547
telemt_desync_frames_bucket_total{bucket="1_2"} 3319
telemt_desync_frames_bucket_total{bucket="3_10"} 3939
telemt_desync_frames_bucket_total{bucket="gt_10"} 3257
telemt_pool_swap_total 134
telemt_pool_force_close_total 3387
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49711
telemt_me_writer_removed_unexpected_total 984
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3750
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3299
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46324
telemt_me_writer_teardown_success_total{mode="normal"} 50743
telemt_me_writer_teardown_noop_total 49715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.722220
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1526371
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 27823674745 (25.91 GB)
telemt_user_octets_to_client{user="hello"} 620521877519 (577.91 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 206109.4 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13611277
telemt_connections_bad_total 1645672
telemt_connections_current 1357
telemt_connections_me_current 1357
telemt_handshake_timeouts_total 399396
telemt_upstream_connect_attempt_total 83120
telemt_upstream_connect_success_total 82753
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 82983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3287
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1627
telemt_me_idle_close_by_peer_total 1627
telemt_me_route_drop_no_conn_total 4539004
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10264307
telemt_me_endpoint_quarantine_total 1527
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1566
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 43120
telemt_desync_full_logged_total 14069
telemt_desync_suppressed_total 29051
telemt_desync_frames_bucket_total{bucket="1_2"} 10493
telemt_desync_frames_bucket_total{bucket="3_10"} 15838
telemt_desync_frames_bucket_total{bucket="gt_10"} 16789
telemt_pool_swap_total 228
telemt_pool_force_close_total 5946
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 75250
telemt_me_writer_removed_unexpected_total 1555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5772
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5772
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69304
telemt_me_writer_teardown_success_total{mode="normal"} 76867
telemt_me_writer_teardown_noop_total 75252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.056790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1436
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10230702
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 197309506444 (183.76 GB)
telemt_user_octets_to_client{user="hello"} 4563644998256 (4.15 TB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 206106.0 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11923010
telemt_connections_bad_total 1391499
telemt_connections_current 1185
telemt_connections_me_current 1185
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 321001
telemt_upstream_connect_attempt_total 111090
telemt_upstream_connect_success_total 110138
telemt_upstream_connect_fail_total 743
telemt_upstream_connect_attempts_per_request{bucket="1"} 110881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 743
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11128
telemt_me_reconnect_success_total 2774
telemt_me_reader_eof_total 2576
telemt_me_idle_close_by_peer_total 2575
telemt_me_seq_mismatch_total 110
telemt_me_route_drop_no_conn_total 5707813
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9185307
telemt_me_endpoint_quarantine_total 1703
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1571
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 42753
telemt_desync_full_logged_total 13766
telemt_desync_suppressed_total 28987
telemt_desync_frames_bucket_total{bucket="1_2"} 11111
telemt_desync_frames_bucket_total{bucket="3_10"} 15707
telemt_desync_frames_bucket_total{bucket="gt_10"} 15935
telemt_pool_swap_total 218
telemt_pool_force_close_total 5695
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 686
telemt_me_draining_writers_reap_progress_total 75703
telemt_me_writer_removed_unexpected_total 2613
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5224
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70008
telemt_me_writer_teardown_success_total{mode="normal"} 78418
telemt_me_writer_teardown_noop_total 75708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154126
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.852906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154126
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 686
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 2211
telemt_me_writer_restored_fallback_total 145
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 9189637
telemt_user_connections_current{user="hello"} 1185
telemt_user_octets_from_client{user="hello"} 159971686836 (148.99 GB)
telemt_user_octets_to_client{user="hello"} 3596714247354 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 176
```