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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 06:27:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35524.9 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741844
telemt_connections_bad_total 41492
telemt_connections_current 1371
telemt_connections_me_current 1371
telemt_handshake_timeouts_total 37269
telemt_upstream_connect_attempt_total 14475
telemt_upstream_connect_success_total 14409
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 14452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 456
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 249125
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556769
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 296
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 2429
telemt_desync_full_logged_total 875
telemt_desync_suppressed_total 1554
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 39
telemt_pool_force_close_total 1064
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 13040
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12266
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11976
telemt_me_writer_teardown_success_total{mode="normal"} 13232
telemt_me_writer_teardown_noop_total 13041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.109615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 556050
telemt_user_connections_current{user="hello"} 1371
telemt_user_octets_from_client{user="hello"} 6638006768 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 175701970616 (163.64 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 35525.9 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1894958
telemt_connections_bad_total 222615
telemt_connections_current 3626
telemt_connections_me_current 3626
telemt_handshake_timeouts_total 56904
telemt_upstream_connect_attempt_total 13503
telemt_upstream_connect_success_total 13447
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 13490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 714
telemt_me_reconnect_success_total 254
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 359831
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1114009
telemt_me_endpoint_quarantine_total 224
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 288
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 4766
telemt_desync_full_logged_total 1659
telemt_desync_suppressed_total 3107
telemt_desync_frames_bucket_total{bucket="1_2"} 979
telemt_desync_frames_bucket_total{bucket="3_10"} 1895
telemt_desync_frames_bucket_total{bucket="gt_10"} 1892
telemt_pool_swap_total 38
telemt_pool_force_close_total 1127
telemt_me_writer_close_signal_drop_total 113
telemt_me_draining_writers_reap_progress_total 12126
telemt_me_writer_removed_unexpected_total 254
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11314
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10999
telemt_me_writer_teardown_success_total{mode="normal"} 12372
telemt_me_writer_teardown_noop_total 12126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24498
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.374301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24498
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 113
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 222
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1111162
telemt_user_connections_current{user="hello"} 3626
telemt_user_octets_from_client{user="hello"} 15361813420 (14.31 GB)
telemt_user_octets_to_client{user="hello"} 457416438592 (426.00 GB)
telemt_user_unique_ips_current{user="hello"} 1359
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 35522.3 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239371
telemt_connections_bad_total 156616
telemt_connections_current 3047
telemt_connections_me_current 3047
telemt_handshake_timeouts_total 58051
telemt_upstream_connect_attempt_total 14573
telemt_upstream_connect_success_total 14565
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 409
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 248
telemt_me_idle_close_by_peer_total 248
telemt_me_route_drop_no_conn_total 291272
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 953519
telemt_me_endpoint_quarantine_total 255
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 286
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
telemt_me_writers_active_current 44
telemt_desync_total 3847
telemt_desync_full_logged_total 1402
telemt_desync_suppressed_total 2445
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 1498
telemt_desync_frames_bucket_total{bucket="gt_10"} 1499
telemt_pool_swap_total 39
telemt_pool_force_close_total 1050
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 13251
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12401
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1046
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12201
telemt_me_writer_teardown_success_total{mode="normal"} 13431
telemt_me_writer_teardown_noop_total 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.732818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 204
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 951450
telemt_user_connections_current{user="hello"} 3047
telemt_user_octets_from_client{user="hello"} 13230350380 (12.32 GB)
telemt_user_octets_to_client{user="hello"} 421827636708 (392.86 GB)
telemt_user_unique_ips_current{user="hello"} 1167
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 35523.6 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079516
telemt_connections_bad_total 146899
telemt_connections_current 2461
telemt_connections_me_current 2461
telemt_handshake_timeouts_total 54195
telemt_upstream_connect_attempt_total 14711
telemt_upstream_connect_success_total 14623
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 14663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 649
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 229171
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725064
telemt_me_endpoint_quarantine_total 252
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3184
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 1991
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 1380
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 39
telemt_pool_force_close_total 1010
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 13189
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 952
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12503
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 992
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12179
telemt_me_writer_teardown_success_total{mode="normal"} 13455
telemt_me_writer_teardown_noop_total 13190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26645
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.144225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26645
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 723783
telemt_user_connections_current{user="hello"} 2461
telemt_user_octets_from_client{user="hello"} 13339181768 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 350558625880 (326.48 GB)
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 35487.5 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1025423
telemt_connections_bad_total 132581
telemt_connections_current 2230
telemt_connections_me_current 2230
telemt_handshake_timeouts_total 37924
telemt_upstream_connect_attempt_total 15144
telemt_upstream_connect_success_total 15135
telemt_upstream_connect_attempts_per_request{bucket="1"} 15135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 227
telemt_me_reader_eof_total 223
telemt_me_idle_close_by_peer_total 223
telemt_me_route_drop_no_conn_total 202600
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718399
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_shadow_rotate_total 286
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
telemt_me_writers_active_current 54
telemt_desync_total 3207
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 1958
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1164
telemt_pool_swap_total 39
telemt_pool_force_close_total 963
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 13717
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13035
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12754
telemt_me_writer_teardown_success_total{mode="normal"} 13941
telemt_me_writer_teardown_noop_total 13718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.436601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27659
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 716967
telemt_user_connections_current{user="hello"} 2230
telemt_user_octets_from_client{user="hello"} 16229950688 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 371198283712 (345.71 GB)
telemt_user_unique_ips_current{user="hello"} 865
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35526.8 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2065130
telemt_connections_bad_total 159144
telemt_connections_current 4188
telemt_connections_me_current 4188
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 142045
telemt_upstream_connect_attempt_total 28375
telemt_upstream_connect_success_total 26999
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 27869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 429
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 373
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 1468687
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1620813
telemt_me_endpoint_quarantine_total 282
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 289
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
telemt_me_writers_active_current 44
telemt_desync_total 3998
telemt_desync_full_logged_total 1523
telemt_desync_suppressed_total 2475
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1692
telemt_desync_frames_bucket_total{bucket="gt_10"} 1396
telemt_pool_swap_total 38
telemt_pool_force_close_total 1083
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 12239
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1017
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11156
telemt_me_writer_teardown_success_total{mode="normal"} 12754
telemt_me_writer_teardown_noop_total 12243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24997
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.288712
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24997
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1632182
telemt_user_connections_current{user="hello"} 4188
telemt_user_octets_from_client{user="hello"} 31506203916 (29.34 GB)
telemt_user_octets_to_client{user="hello"} 437923029695 (407.85 GB)
telemt_user_msgs_from_client{user="hello"} 40291
telemt_user_msgs_to_client{user="hello"} 96775
telemt_user_unique_ips_current{user="hello"} 1541
telemt_user_unique_ips_recent_window{user="hello"} 829
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 35494.3 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091041
telemt_connections_bad_total 146439
telemt_connections_current 2268
telemt_connections_me_current 2268
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 23358
telemt_upstream_connect_attempt_total 16637
telemt_upstream_connect_success_total 16491
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 16621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_reconnect_attempts_total 1316
telemt_me_reconnect_success_total 323
telemt_me_reader_eof_total 335
telemt_me_idle_close_by_peer_total 335
telemt_me_route_drop_no_conn_total 259493
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787504
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 46
telemt_desync_total 3147
telemt_desync_full_logged_total 1198
telemt_desync_suppressed_total 1949
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 1295
telemt_desync_frames_bucket_total{bucket="gt_10"} 1262
telemt_pool_swap_total 39
telemt_pool_force_close_total 924
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 13685
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12993
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12761
telemt_me_writer_teardown_success_total{mode="normal"} 14020
telemt_me_writer_teardown_noop_total 13685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.009664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 785154
telemt_user_connections_current{user="hello"} 2268
telemt_user_octets_from_client{user="hello"} 12753503676 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 396103795330 (368.90 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 900
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35488.7 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1381891
telemt_connections_bad_total 87766
telemt_connections_current 2353
telemt_connections_me_current 2353
telemt_handshake_timeouts_total 487986
telemt_upstream_connect_attempt_total 15840
telemt_upstream_connect_success_total 15813
telemt_upstream_connect_attempts_per_request{bucket="1"} 15813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 316
telemt_me_reconnect_success_total 234
telemt_me_reader_eof_total 242
telemt_me_idle_close_by_peer_total 242
telemt_me_route_drop_no_conn_total 227521
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701407
telemt_me_endpoint_quarantine_total 306
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 3082
telemt_desync_full_logged_total 1107
telemt_desync_suppressed_total 1975
telemt_desync_frames_bucket_total{bucket="1_2"} 575
telemt_desync_frames_bucket_total{bucket="3_10"} 1260
telemt_desync_frames_bucket_total{bucket="gt_10"} 1247
telemt_pool_swap_total 39
telemt_pool_force_close_total 892
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 14178
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13588
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13286
telemt_me_writer_teardown_success_total{mode="normal"} 14421
telemt_me_writer_teardown_noop_total 14178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28599
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.512716
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28599
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 698528
telemt_user_connections_current{user="hello"} 2353
telemt_user_octets_from_client{user="hello"} 11407855332 (10.62 GB)
telemt_user_octets_to_client{user="hello"} 364892850596 (339.83 GB)
telemt_user_unique_ips_current{user="hello"} 966
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 33480.3 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261557
telemt_connections_bad_total 10875
telemt_connections_current 464
telemt_connections_me_current 464
telemt_handshake_timeouts_total 68740
telemt_upstream_connect_attempt_total 17184
telemt_upstream_connect_success_total 17183
telemt_upstream_connect_attempts_per_request{bucket="1"} 17183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 519
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 63384
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171604
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1052
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 37
telemt_pool_force_close_total 713
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 15279
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1055
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14483
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 713
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14566
telemt_me_writer_teardown_success_total{mode="normal"} 15538
telemt_me_writer_teardown_noop_total 15279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30817
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.946761
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30817
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 171846
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 1862698559 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 71253809957 (66.36 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 35498.7 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124780
telemt_connections_bad_total 85099
telemt_connections_current 2973
telemt_connections_me_current 2973
telemt_handshake_timeouts_total 29761
telemt_upstream_connect_attempt_total 16298
telemt_upstream_connect_success_total 16225
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 16269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 572
telemt_me_reconnect_success_total 327
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 237965
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 868752
telemt_me_endpoint_quarantine_total 296
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3404
telemt_desync_full_logged_total 1132
telemt_desync_suppressed_total 2272
telemt_desync_frames_bucket_total{bucket="1_2"} 923
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1196
telemt_pool_swap_total 39
telemt_pool_force_close_total 905
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 14710
telemt_me_writer_removed_unexpected_total 313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14004
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 905
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13805
telemt_me_writer_teardown_success_total{mode="normal"} 15030
telemt_me_writer_teardown_noop_total 14710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.610914
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 864476
telemt_user_connections_current{user="hello"} 2973
telemt_user_octets_from_client{user="hello"} 13257072356 (12.35 GB)
telemt_user_octets_to_client{user="hello"} 390628059752 (363.80 GB)
telemt_user_unique_ips_current{user="hello"} 1067
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 35495.5 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1068652
telemt_connections_bad_total 67479
telemt_connections_current 2640
telemt_connections_me_current 2641
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 28786
telemt_upstream_connect_attempt_total 24861
telemt_upstream_connect_success_total 24685
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 24823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2453
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 244022
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846888
telemt_me_endpoint_quarantine_total 363
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 288
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
telemt_me_writers_active_current 46
telemt_desync_total 3200
telemt_desync_full_logged_total 1023
telemt_desync_suppressed_total 2177
telemt_desync_frames_bucket_total{bucket="1_2"} 969
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1070
telemt_pool_swap_total 39
telemt_pool_force_close_total 874
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 13950
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13149
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13076
telemt_me_writer_teardown_success_total{mode="normal"} 14363
telemt_me_writer_teardown_noop_total 13950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28313
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.342730
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28313
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 322
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 851502
telemt_user_connections_current{user="hello"} 2641
telemt_user_octets_from_client{user="hello"} 10778748655 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 372744558891 (347.15 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1004
telemt_user_unique_ips_recent_window{user="hello"} 355
```