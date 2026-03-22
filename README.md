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

# Server Metrics 2026-03-22 10:36:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48587.6 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1299852
telemt_connections_bad_total 68166
telemt_connections_current 1991
telemt_connections_me_current 1991
telemt_handshake_timeouts_total 60026
telemt_upstream_connect_attempt_total 18756
telemt_upstream_connect_success_total 18755
telemt_upstream_connect_attempts_per_request{bucket="1"} 18755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 561
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 290
telemt_me_idle_close_by_peer_total 290
telemt_me_route_drop_no_conn_total 708358
telemt_me_route_drop_channel_closed_total 335
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1086155
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_shadow_rotate_total 388
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 7203
telemt_desync_full_logged_total 2111
telemt_desync_suppressed_total 5092
telemt_desync_frames_bucket_total{bucket="1_2"} 2095
telemt_desync_frames_bucket_total{bucket="3_10"} 2718
telemt_desync_frames_bucket_total{bucket="gt_10"} 2390
telemt_pool_swap_total 53
telemt_pool_force_close_total 1545
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 17077
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1180
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16102
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 33
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15532
telemt_me_writer_teardown_success_total{mode="normal"} 17282
telemt_me_writer_teardown_noop_total 17079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 88.461275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1084251
telemt_user_connections_current{user="hello"} 1991
telemt_user_octets_from_client{user="hello"} 17384797116 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 343443358356 (319.86 GB)
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 61954.0 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2096839
telemt_connections_bad_total 174674
telemt_connections_current 1742
telemt_connections_me_current 1742
telemt_handshake_timeouts_total 50251
telemt_upstream_connect_attempt_total 36458
telemt_upstream_connect_success_total 35967
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 36398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3155
telemt_me_reconnect_success_total 1409
telemt_me_reader_eof_total 1297
telemt_me_idle_close_by_peer_total 1297
telemt_me_route_drop_no_conn_total 1571599
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1643981
telemt_me_endpoint_quarantine_total 529
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 490
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 44
telemt_desync_total 6817
telemt_desync_full_logged_total 3857
telemt_desync_suppressed_total 2960
telemt_desync_frames_bucket_total{bucket="1_2"} 1552
telemt_desync_frames_bucket_total{bucket="3_10"} 2667
telemt_desync_frames_bucket_total{bucket="gt_10"} 2598
telemt_pool_swap_total 62
telemt_pool_force_close_total 1754
telemt_me_writer_close_signal_drop_total 144
telemt_me_draining_writers_reap_progress_total 24973
telemt_me_writer_removed_unexpected_total 1263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2713
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23517
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23219
telemt_me_writer_teardown_success_total{mode="normal"} 26230
telemt_me_writer_teardown_noop_total 24973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51203
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.555534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51203
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 144
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1172
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1649955
telemt_user_connections_current{user="hello"} 1742
telemt_user_octets_from_client{user="hello"} 22466420278 (20.92 GB)
telemt_user_octets_to_client{user="hello"} 454331684804 (423.13 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1191
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 136813.6 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11398596
telemt_connections_bad_total 968138
telemt_connections_current 4762
telemt_connections_me_current 4762
telemt_handshake_timeouts_total 311703
telemt_upstream_connect_attempt_total 49942
telemt_upstream_connect_success_total 49862
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2140
telemt_me_reconnect_success_total 1100
telemt_me_reader_eof_total 1081
telemt_me_idle_close_by_peer_total 1080
telemt_me_route_drop_no_conn_total 8275283
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9076095
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1018
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 37724
telemt_desync_full_logged_total 12210
telemt_desync_suppressed_total 25514
telemt_desync_frames_bucket_total{bucket="1_2"} 8494
telemt_desync_frames_bucket_total{bucket="3_10"} 14661
telemt_desync_frames_bucket_total{bucket="gt_10"} 14569
telemt_pool_swap_total 147
telemt_pool_force_close_total 4942
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 770
telemt_me_draining_writers_reap_progress_total 45552
telemt_me_writer_removed_unexpected_total 1041
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42125
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 333
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40610
telemt_me_writer_teardown_success_total{mode="normal"} 46017
telemt_me_writer_teardown_noop_total 45596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.701199
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 770
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 9065415
telemt_user_connections_current{user="hello"} 4762
telemt_user_octets_from_client{user="hello"} 140448376204 (130.80 GB)
telemt_user_octets_to_client{user="hello"} 2704394227312 (2.46 TB)
telemt_user_unique_ips_current{user="hello"} 1635
telemt_user_unique_ips_recent_window{user="hello"} 912
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 136815.2 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8876878
telemt_connections_bad_total 794272
telemt_connections_current 4449
telemt_connections_me_current 4449
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 272305
telemt_upstream_connect_attempt_total 56371
telemt_upstream_connect_success_total 55803
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 56063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3083
telemt_me_reconnect_success_total 1235
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 3594442
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6608347
telemt_me_endpoint_quarantine_total 860
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1048
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 85
telemt_desync_total 29824
telemt_desync_full_logged_total 10107
telemt_desync_suppressed_total 19717
telemt_desync_frames_bucket_total{bucket="1_2"} 7241
telemt_desync_frames_bucket_total{bucket="3_10"} 11493
telemt_desync_frames_bucket_total{bucket="gt_10"} 11090
telemt_pool_swap_total 147
telemt_pool_force_close_total 4461
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 497
telemt_me_draining_writers_reap_progress_total 43980
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3829
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41204
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39519
telemt_me_writer_teardown_success_total{mode="normal"} 45033
telemt_me_writer_teardown_noop_total 43986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 64.448850
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 497
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1054
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6530149
telemt_user_connections_current{user="hello"} 4449
telemt_user_octets_from_client{user="hello"} 172039528119 (160.22 GB)
telemt_user_octets_to_client{user="hello"} 3016308595274 (2.74 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1767
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 136779.3 (37h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8423959
telemt_connections_bad_total 704314
telemt_connections_current 4315
telemt_connections_me_current 4315
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 271824
telemt_upstream_connect_attempt_total 60710
telemt_upstream_connect_success_total 60008
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3529
telemt_me_reconnect_success_total 1480
telemt_me_reader_eof_total 1363
telemt_me_idle_close_by_peer_total 1363
telemt_me_route_drop_no_conn_total 3555736
telemt_me_route_drop_channel_closed_total 235
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6314359
telemt_me_endpoint_quarantine_total 941
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1001
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 44
telemt_desync_total 29242
telemt_desync_full_logged_total 9949
telemt_desync_suppressed_total 19293
telemt_desync_frames_bucket_total{bucket="1_2"} 7050
telemt_desync_frames_bucket_total{bucket="3_10"} 11271
telemt_desync_frames_bucket_total{bucket="gt_10"} 10921
telemt_pool_swap_total 144
telemt_pool_force_close_total 4394
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 44840
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4205
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41971
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40446
telemt_me_writer_teardown_success_total{mode="normal"} 46176
telemt_me_writer_teardown_noop_total 44857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.322337
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1301
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 6306137
telemt_user_connections_current{user="hello"} 4315
telemt_user_octets_from_client{user="hello"} 156713743779 (145.95 GB)
telemt_user_octets_to_client{user="hello"} 2745986517403 (2.50 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1783
telemt_user_unique_ips_recent_window{user="hello"} 742
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7059.2 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3015779
telemt_connections_bad_total 205536
telemt_connections_current 6701
telemt_connections_me_current 6701
telemt_handshake_timeouts_total 44324
telemt_upstream_connect_attempt_total 9129
telemt_upstream_connect_success_total 8652
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 8997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2707
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 491
telemt_me_reconnect_success_total 195
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 6922540
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2518344
telemt_me_endpoint_quarantine_total 40
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 3801
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 2830
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 1476
telemt_desync_frames_bucket_total{bucket="gt_10"} 1653
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_me_writer_close_signal_drop_total 88
telemt_me_draining_writers_reap_progress_total 1872
telemt_me_writer_removed_unexpected_total 182
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1639
telemt_me_writer_teardown_success_total{mode="normal"} 2039
telemt_me_writer_teardown_noop_total 1873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.834436
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 88
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 138
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2522683
telemt_user_connections_current{user="hello"} 6701
telemt_user_octets_from_client{user="hello"} 13239068058 (12.33 GB)
telemt_user_octets_to_client{user="hello"} 74007602275 (68.92 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2448
telemt_user_unique_ips_recent_window{user="hello"} 1408
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 136786.1 (37h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8112313
telemt_connections_bad_total 702861
telemt_connections_current 4680
telemt_connections_me_current 4680
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 165186
telemt_upstream_connect_attempt_total 85962
telemt_upstream_connect_success_total 85109
telemt_upstream_connect_fail_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 85842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 733
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70630
telemt_me_reconnect_success_total 2173
telemt_me_reader_eof_total 1909
telemt_me_idle_close_by_peer_total 1908
telemt_me_route_drop_no_conn_total 3565627
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6408786
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1027
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 32355
telemt_desync_full_logged_total 11161
telemt_desync_suppressed_total 21194
telemt_desync_frames_bucket_total{bucket="1_2"} 6583
telemt_desync_frames_bucket_total{bucket="3_10"} 12454
telemt_desync_frames_bucket_total{bucket="gt_10"} 13318
telemt_pool_swap_total 141
telemt_pool_force_close_total 4096
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 496
telemt_me_draining_writers_reap_progress_total 47173
telemt_me_writer_removed_unexpected_total 1938
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44266
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3569
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 527
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43077
telemt_me_writer_teardown_success_total{mode="normal"} 49136
telemt_me_writer_teardown_noop_total 47174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.441974
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 496
telemt_me_refill_failed_total 4233
telemt_me_writer_restored_same_endpoint_total 1805
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6412495
telemt_user_connections_current{user="hello"} 4680
telemt_user_octets_from_client{user="hello"} 155279792399 (144.62 GB)
telemt_user_octets_to_client{user="hello"} 2548335191785 (2.32 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1884
telemt_user_unique_ips_recent_window{user="hello"} 685
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 73622.0 (20h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7107852
telemt_connections_bad_total 266854
telemt_connections_current 4387
telemt_connections_me_current 4387
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2904401
telemt_upstream_connect_attempt_total 38508
telemt_upstream_connect_success_total 38229
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 38501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_reconnect_attempts_total 47664
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 988
telemt_me_route_drop_no_conn_total 2176905
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3523531
telemt_me_endpoint_quarantine_total 504
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 560
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 18936
telemt_desync_full_logged_total 6360
telemt_desync_suppressed_total 12576
telemt_desync_frames_bucket_total{bucket="1_2"} 3867
telemt_desync_frames_bucket_total{bucket="3_10"} 7275
telemt_desync_frames_bucket_total{bucket="gt_10"} 7794
telemt_pool_swap_total 77
telemt_pool_force_close_total 2365
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 26297
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25033
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 354
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23932
telemt_me_writer_teardown_success_total{mode="normal"} 27378
telemt_me_writer_teardown_noop_total 26303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.990027
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 2694
telemt_me_writer_restored_same_endpoint_total 1181
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3522549
telemt_user_connections_current{user="hello"} 4387
telemt_user_octets_from_client{user="hello"} 83995580880 (78.23 GB)
telemt_user_octets_to_client{user="hello"} 1439477786858 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1717
telemt_user_unique_ips_recent_window{user="hello"} 645
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 54592.7 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554436
telemt_connections_bad_total 3835
telemt_connections_current 1017
telemt_connections_me_current 1017
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10323
telemt_upstream_connect_attempt_total 28654
telemt_upstream_connect_success_total 28589
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1203
telemt_me_reconnect_success_total 510
telemt_me_reader_eof_total 507
telemt_me_idle_close_by_peer_total 507
telemt_me_route_drop_no_conn_total 181885
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502007
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 464
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 92
telemt_desync_total 2548
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1817
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 57
telemt_pool_force_close_total 1354
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 23210
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1728
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21990
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21856
telemt_me_writer_teardown_success_total{mode="normal"} 23718
telemt_me_writer_teardown_noop_total 23210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46928
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.445499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46928
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 503973
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 9811540765 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 241209293319 (224.64 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 136790.4 (37h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9862119
telemt_connections_bad_total 1151821
telemt_connections_current 5812
telemt_connections_me_current 5812
telemt_handshake_timeouts_total 264671
telemt_upstream_connect_attempt_total 52495
telemt_upstream_connect_success_total 52295
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 52449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2033
telemt_me_reconnect_success_total 1081
telemt_me_reader_eof_total 1048
telemt_me_idle_close_by_peer_total 1048
telemt_me_route_drop_no_conn_total 2831969
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7345046
telemt_me_endpoint_quarantine_total 963
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1032
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 29868
telemt_desync_full_logged_total 9787
telemt_desync_suppressed_total 20081
telemt_desync_frames_bucket_total{bucket="1_2"} 7341
telemt_desync_frames_bucket_total{bucket="3_10"} 10932
telemt_desync_frames_bucket_total{bucket="gt_10"} 11595
telemt_pool_swap_total 151
telemt_pool_force_close_total 4088
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 47345
telemt_me_writer_removed_unexpected_total 1007
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44571
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43257
telemt_me_writer_teardown_success_total{mode="normal"} 48384
telemt_me_writer_teardown_noop_total 47347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95731
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.058551
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95731
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7317100
telemt_user_connections_current{user="hello"} 5812
telemt_user_octets_from_client{user="hello"} 141661825464 (131.93 GB)
telemt_user_octets_to_client{user="hello"} 3404657620328 (3.10 TB)
telemt_user_unique_ips_current{user="hello"} 2223
telemt_user_unique_ips_recent_window{user="hello"} 783
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 136787.0 (37h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8573560
telemt_connections_bad_total 963690
telemt_connections_current 4935
telemt_connections_me_current 4935
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 221542
telemt_upstream_connect_attempt_total 77010
telemt_upstream_connect_success_total 76463
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 76941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1968
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_reconnect_attempts_total 6590
telemt_me_reconnect_success_total 1549
telemt_me_reader_eof_total 1374
telemt_me_idle_close_by_peer_total 1374
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 3074021
telemt_me_route_drop_channel_closed_total 269
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6551471
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1033
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 28995
telemt_desync_full_logged_total 9560
telemt_desync_suppressed_total 19435
telemt_desync_frames_bucket_total{bucket="1_2"} 7148
telemt_desync_frames_bucket_total{bucket="3_10"} 10711
telemt_desync_frames_bucket_total{bucket="gt_10"} 11136
telemt_pool_swap_total 148
telemt_pool_force_close_total 4018
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 496
telemt_me_draining_writers_reap_progress_total 46034
telemt_me_writer_removed_unexpected_total 1392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3720
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 298
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42016
telemt_me_writer_teardown_success_total{mode="normal"} 47489
telemt_me_writer_teardown_noop_total 46038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93527
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.631304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93527
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 496
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1206
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6559583
telemt_user_connections_current{user="hello"} 4935
telemt_user_octets_from_client{user="hello"} 118876429005 (110.71 GB)
telemt_user_octets_to_client{user="hello"} 2759494897015 (2.51 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1847
telemt_user_unique_ips_recent_window{user="hello"} 670
```