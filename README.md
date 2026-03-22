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

# Server Metrics 2026-03-22 11:52:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 53177.4 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1554893
telemt_connections_bad_total 74282
telemt_connections_current 1998
telemt_connections_me_current 1998
telemt_handshake_timeouts_total 70473
telemt_upstream_connect_attempt_total 20328
telemt_upstream_connect_success_total 20327
telemt_upstream_connect_attempts_per_request{bucket="1"} 20327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 752
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 1043385
telemt_me_route_drop_channel_closed_total 462
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1313411
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 425
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 41
telemt_me_writers_warm_current 36
telemt_desync_total 7953
telemt_desync_full_logged_total 2375
telemt_desync_suppressed_total 5578
telemt_desync_frames_bucket_total{bucket="1_2"} 2268
telemt_desync_frames_bucket_total{bucket="3_10"} 2979
telemt_desync_frames_bucket_total{bucket="gt_10"} 2706
telemt_pool_swap_total 58
telemt_pool_force_close_total 1731
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 18496
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1297
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17406
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1696
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16765
telemt_me_writer_teardown_success_total{mode="normal"} 18703
telemt_me_writer_teardown_noop_total 18498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37201
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 128.737521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37201
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1310892
telemt_user_connections_current{user="hello"} 1998
telemt_user_octets_from_client{user="hello"} 20714243860 (19.29 GB)
telemt_user_octets_to_client{user="hello"} 391161441448 (364.30 GB)
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 66543.5 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2518315
telemt_connections_bad_total 218957
telemt_connections_current 2038
telemt_connections_me_current 2038
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 57598
telemt_upstream_connect_attempt_total 44266
telemt_upstream_connect_success_total 43751
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 44206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3399
telemt_me_reconnect_success_total 1510
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1393
telemt_me_route_drop_no_conn_total 2190612
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981596
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 521
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
telemt_me_writers_active_current 43
telemt_desync_total 7810
telemt_desync_full_logged_total 4411
telemt_desync_suppressed_total 3399
telemt_desync_frames_bucket_total{bucket="1_2"} 1805
telemt_desync_frames_bucket_total{bucket="3_10"} 3046
telemt_desync_frames_bucket_total{bucket="gt_10"} 2959
telemt_pool_swap_total 66
telemt_pool_force_close_total 1865
telemt_me_writer_close_signal_drop_total 155
telemt_me_draining_writers_reap_progress_total 26519
telemt_me_writer_removed_unexpected_total 1355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24958
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24654
telemt_me_writer_teardown_success_total{mode="normal"} 27872
telemt_me_writer_teardown_noop_total 26519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.115105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 155
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1255
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1993421
telemt_user_connections_current{user="hello"} 2038
telemt_user_octets_from_client{user="hello"} 25003909479 (23.29 GB)
telemt_user_octets_to_client{user="hello"} 493120149766 (459.25 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1183
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 141403.6 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12520778
telemt_connections_bad_total 1088330
telemt_connections_current 5593
telemt_connections_me_current 5593
telemt_handshake_timeouts_total 326518
telemt_upstream_connect_attempt_total 51386
telemt_upstream_connect_success_total 51306
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2213
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 10188871
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10003612
telemt_me_endpoint_quarantine_total 893
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1053
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
telemt_me_writers_active_current 51
telemt_me_writers_warm_current 18
telemt_desync_total 41036
telemt_desync_full_logged_total 13148
telemt_desync_suppressed_total 27888
telemt_desync_frames_bucket_total{bucket="1_2"} 9249
telemt_desync_frames_bucket_total{bucket="3_10"} 16030
telemt_desync_frames_bucket_total{bucket="gt_10"} 15757
telemt_pool_swap_total 152
telemt_pool_force_close_total 5130
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 803
telemt_me_draining_writers_reap_progress_total 46842
telemt_me_writer_removed_unexpected_total 1070
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4019
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43288
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 343
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41712
telemt_me_writer_teardown_success_total{mode="normal"} 47307
telemt_me_writer_teardown_noop_total 46886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.576448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 803
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 991
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 9992406
telemt_user_connections_current{user="hello"} 5593
telemt_user_octets_from_client{user="hello"} 147862103840 (137.71 GB)
telemt_user_octets_to_client{user="hello"} 2801971244740 (2.55 TB)
telemt_user_unique_ips_current{user="hello"} 2278
telemt_user_unique_ips_recent_window{user="hello"} 845
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 141404.7 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9395528
telemt_connections_bad_total 852412
telemt_connections_current 4300
telemt_connections_me_current 4300
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 285518
telemt_upstream_connect_attempt_total 57910
telemt_upstream_connect_success_total 57329
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 57596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3262
telemt_me_reconnect_success_total 1326
telemt_me_reader_eof_total 1212
telemt_me_idle_close_by_peer_total 1212
telemt_me_route_drop_no_conn_total 3797798
telemt_me_route_drop_channel_closed_total 387
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7008714
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1077
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
telemt_me_writers_warm_current 35
telemt_desync_total 31800
telemt_desync_full_logged_total 10752
telemt_desync_suppressed_total 21048
telemt_desync_frames_bucket_total{bucket="1_2"} 7827
telemt_desync_frames_bucket_total{bucket="3_10"} 12241
telemt_desync_frames_bucket_total{bucket="gt_10"} 11732
telemt_pool_swap_total 151
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 541
telemt_me_draining_writers_reap_progress_total 45307
telemt_me_writer_removed_unexpected_total 1245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4009
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42437
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40674
telemt_me_writer_teardown_success_total{mode="normal"} 46446
telemt_me_writer_teardown_noop_total 45315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91761
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 71.536553
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91761
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 541
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6929934
telemt_user_connections_current{user="hello"} 4300
telemt_user_octets_from_client{user="hello"} 181249706711 (168.80 GB)
telemt_user_octets_to_client{user="hello"} 3187194475546 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1704
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 141368.7 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8899094
telemt_connections_bad_total 746379
telemt_connections_current 4540
telemt_connections_me_current 4540
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 283421
telemt_upstream_connect_attempt_total 62300
telemt_upstream_connect_success_total 61573
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3776
telemt_me_reconnect_success_total 1589
telemt_me_reader_eof_total 1473
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 3780477
telemt_me_route_drop_channel_closed_total 262
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6694096
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1031
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 87
telemt_me_writers_warm_current 17
telemt_desync_total 31245
telemt_desync_full_logged_total 10513
telemt_desync_suppressed_total 20732
telemt_desync_frames_bucket_total{bucket="1_2"} 7749
telemt_desync_frames_bucket_total{bucket="3_10"} 12019
telemt_desync_frames_bucket_total{bucket="gt_10"} 11477
telemt_pool_swap_total 147
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 540
telemt_me_draining_writers_reap_progress_total 46094
telemt_me_writer_removed_unexpected_total 1505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4400
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43137
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41572
telemt_me_writer_teardown_success_total{mode="normal"} 47537
telemt_me_writer_teardown_noop_total 46111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93648
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.239322
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93648
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 540
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1408
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6685281
telemt_user_connections_current{user="hello"} 4540
telemt_user_octets_from_client{user="hello"} 163923858475 (152.67 GB)
telemt_user_octets_to_client{user="hello"} 2894669185503 (2.63 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1888
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 11648.5 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4946400
telemt_connections_bad_total 304147
telemt_connections_current 6834
telemt_connections_me_current 6834
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 78309
telemt_upstream_connect_attempt_total 23413
telemt_upstream_connect_success_total 22362
telemt_upstream_connect_fail_total 835
telemt_upstream_connect_attempts_per_request{bucket="1"} 23197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4622
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 835
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 2277
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 211
telemt_me_idle_close_by_peer_total 211
telemt_me_route_drop_no_conn_total 11536876
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4137307
telemt_me_endpoint_quarantine_total 78
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 6064
telemt_desync_full_logged_total 1574
telemt_desync_suppressed_total 4490
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 2433
telemt_desync_frames_bucket_total{bucket="gt_10"} 2494
telemt_pool_swap_total 10
telemt_pool_force_close_total 435
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 3005
telemt_me_writer_removed_unexpected_total 300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2721
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2570
telemt_me_writer_teardown_success_total{mode="normal"} 3268
telemt_me_writer_teardown_noop_total 3008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.484411
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4152519
telemt_user_connections_current{user="hello"} 6834
telemt_user_octets_from_client{user="hello"} 22282235426 (20.75 GB)
telemt_user_octets_to_client{user="hello"} 120680817323 (112.39 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2429
telemt_user_unique_ips_recent_window{user="hello"} 1331
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 141375.4 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8648000
telemt_connections_bad_total 741603
telemt_connections_current 4682
telemt_connections_me_current 4682
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 181830
telemt_upstream_connect_attempt_total 87372
telemt_upstream_connect_success_total 86503
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 87251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70716
telemt_me_reconnect_success_total 2217
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1946
telemt_me_route_drop_no_conn_total 3909143
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6833847
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1058
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 24
telemt_desync_total 34895
telemt_desync_full_logged_total 12012
telemt_desync_suppressed_total 22883
telemt_desync_frames_bucket_total{bucket="1_2"} 7134
telemt_desync_frames_bucket_total{bucket="3_10"} 13396
telemt_desync_frames_bucket_total{bucket="gt_10"} 14365
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 48374
telemt_me_writer_removed_unexpected_total 1976
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4989
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44121
telemt_me_writer_teardown_success_total{mode="normal"} 50375
telemt_me_writer_teardown_noop_total 48375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98750
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.844016
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98750
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1840
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6836678
telemt_user_connections_current{user="hello"} 4682
telemt_user_octets_from_client{user="hello"} 163026059107 (151.83 GB)
telemt_user_octets_to_client{user="hello"} 2669751750021 (2.43 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1976
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 78211.4 (21h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7979523
telemt_connections_bad_total 287828
telemt_connections_current 4622
telemt_connections_me_current 4622
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3316373
telemt_upstream_connect_attempt_total 39826
telemt_upstream_connect_success_total 39539
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 39819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_reconnect_attempts_total 47793
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 2583368
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3907001
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 593
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 21456
telemt_desync_full_logged_total 7185
telemt_desync_suppressed_total 14271
telemt_desync_frames_bucket_total{bucket="1_2"} 4394
telemt_desync_frames_bucket_total{bucket="3_10"} 8301
telemt_desync_frames_bucket_total{bucket="gt_10"} 8761
telemt_pool_swap_total 82
telemt_pool_force_close_total 2520
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 27475
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2447
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26137
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24955
telemt_me_writer_teardown_success_total{mode="normal"} 28584
telemt_me_writer_teardown_noop_total 27482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56066
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.681518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56066
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3904502
telemt_user_connections_current{user="hello"} 4622
telemt_user_octets_from_client{user="hello"} 89768823348 (83.60 GB)
telemt_user_octets_to_client{user="hello"} 1561172390402 (1.42 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1774
telemt_user_unique_ips_recent_window{user="hello"} 682
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 59182.3 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641736
telemt_connections_bad_total 6495
telemt_connections_current 953
telemt_connections_me_current 953
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12310
telemt_upstream_connect_attempt_total 30647
telemt_upstream_connect_success_total 30573
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 30637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 213284
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 579067
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 498
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_writers_active_current 48
telemt_desync_total 3217
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 2287
telemt_desync_frames_bucket_total{bucket="1_2"} 821
telemt_desync_frames_bucket_total{bucket="3_10"} 1270
telemt_desync_frames_bucket_total{bucket="gt_10"} 1126
telemt_pool_swap_total 62
telemt_pool_force_close_total 1517
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 24994
telemt_me_writer_removed_unexpected_total 545
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23677
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1441
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23477
telemt_me_writer_teardown_success_total{mode="normal"} 25558
telemt_me_writer_teardown_noop_total 24994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.703029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 580933
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 10973551737 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 271623246207 (252.97 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 141379.8 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10475442
telemt_connections_bad_total 1228068
telemt_connections_current 5823
telemt_connections_me_current 5823
telemt_handshake_timeouts_total 277055
telemt_upstream_connect_attempt_total 53863
telemt_upstream_connect_success_total 53654
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 53815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_reconnect_attempts_total 2096
telemt_me_reconnect_success_total 1108
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1076
telemt_me_route_drop_no_conn_total 3066527
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 30
telemt_me_route_drop_queue_full_profile_total{profile="high"} 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7829751
telemt_me_endpoint_quarantine_total 980
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1061
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 21
telemt_desync_total 32054
telemt_desync_full_logged_total 10545
telemt_desync_suppressed_total 21509
telemt_desync_frames_bucket_total{bucket="1_2"} 7760
telemt_desync_frames_bucket_total{bucket="3_10"} 11778
telemt_desync_frames_bucket_total{bucket="gt_10"} 12516
telemt_pool_swap_total 156
telemt_pool_force_close_total 4250
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 48552
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3938
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45681
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44302
telemt_me_writer_teardown_success_total{mode="normal"} 49619
telemt_me_writer_teardown_noop_total 48554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.025269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 967
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 7801193
telemt_user_connections_current{user="hello"} 5823
telemt_user_octets_from_client{user="hello"} 151700728016 (141.28 GB)
telemt_user_octets_to_client{user="hello"} 3611976633976 (3.29 TB)
telemt_user_unique_ips_current{user="hello"} 2197
telemt_user_unique_ips_recent_window{user="hello"} 777
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 141376.5 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9169091
telemt_connections_bad_total 1037054
telemt_connections_current 4538
telemt_connections_me_current 4538
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 237329
telemt_upstream_connect_attempt_total 78419
telemt_upstream_connect_success_total 77853
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 78348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1971
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_reconnect_attempts_total 6658
telemt_me_reconnect_success_total 1591
telemt_me_reader_eof_total 1412
telemt_me_idle_close_by_peer_total 1412
telemt_me_seq_mismatch_total 67
telemt_me_route_drop_no_conn_total 3572458
telemt_me_route_drop_channel_closed_total 284
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7029741
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1069
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_warm_current 19
telemt_desync_total 31340
telemt_desync_full_logged_total 10273
telemt_desync_suppressed_total 21067
telemt_desync_frames_bucket_total{bucket="1_2"} 7713
telemt_desync_frames_bucket_total{bucket="3_10"} 11636
telemt_desync_frames_bucket_total{bucket="gt_10"} 11991
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 47241
telemt_me_writer_removed_unexpected_total 1431
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44137
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43062
telemt_me_writer_teardown_success_total{mode="normal"} 48737
telemt_me_writer_teardown_noop_total 47245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95982
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.096360
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95982
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1241
telemt_me_writer_restored_fallback_total 91
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 7037498
telemt_user_connections_current{user="hello"} 4538
telemt_user_octets_from_client{user="hello"} 126010029713 (117.36 GB)
telemt_user_octets_to_client{user="hello"} 2879092491879 (2.62 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1858
telemt_user_unique_ips_recent_window{user="hello"} 643
```