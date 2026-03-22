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

# Server Metrics 2026-03-22 10:10:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47040.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1231068
telemt_connections_bad_total 65047
telemt_connections_current 1761
telemt_connections_me_current 1761
telemt_handshake_timeouts_total 56455
telemt_upstream_connect_attempt_total 18279
telemt_upstream_connect_success_total 18277
telemt_upstream_connect_attempts_per_request{bucket="1"} 18277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 552
telemt_me_reconnect_success_total 283
telemt_me_reader_eof_total 283
telemt_me_idle_close_by_peer_total 283
telemt_me_route_drop_no_conn_total 683432
telemt_me_route_drop_channel_closed_total 293
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027222
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_active_current 45
telemt_desync_total 7003
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 4964
telemt_desync_frames_bucket_total{bucket="1_2"} 2044
telemt_desync_frames_bucket_total{bucket="3_10"} 2649
telemt_desync_frames_bucket_total{bucket="gt_10"} 2310
telemt_pool_swap_total 52
telemt_pool_force_close_total 1516
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 16639
telemt_me_writer_removed_unexpected_total 279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15685
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15123
telemt_me_writer_teardown_success_total{mode="normal"} 16836
telemt_me_writer_teardown_noop_total 16641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 81.565737
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1025408
telemt_user_connections_current{user="hello"} 1761
telemt_user_octets_from_client{user="hello"} 16163134920 (15.05 GB)
telemt_user_octets_to_client{user="hello"} 324837316188 (302.53 GB)
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 60407.3 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904102
telemt_connections_bad_total 167281
telemt_connections_current 2690
telemt_connections_me_current 2690
telemt_handshake_timeouts_total 48214
telemt_upstream_connect_attempt_total 35887
telemt_upstream_connect_success_total 35411
telemt_upstream_connect_fail_total 418
telemt_upstream_connect_attempts_per_request{bucket="1"} 35829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 418
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3127
telemt_me_reconnect_success_total 1380
telemt_me_reader_eof_total 1277
telemt_me_idle_close_by_peer_total 1277
telemt_me_route_drop_no_conn_total 1193849
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1473539
telemt_me_endpoint_quarantine_total 511
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 475
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_warm_current 29
telemt_desync_total 6340
telemt_desync_full_logged_total 3615
telemt_desync_suppressed_total 2725
telemt_desync_frames_bucket_total{bucket="1_2"} 1421
telemt_desync_frames_bucket_total{bucket="3_10"} 2478
telemt_desync_frames_bucket_total{bucket="gt_10"} 2441
telemt_pool_swap_total 60
telemt_pool_force_close_total 1692
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 24450
telemt_me_writer_removed_unexpected_total 1244
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23034
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 179
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22758
telemt_me_writer_teardown_success_total{mode="normal"} 25687
telemt_me_writer_teardown_noop_total 24450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.544085
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1154
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1479611
telemt_user_connections_current{user="hello"} 2690
telemt_user_octets_from_client{user="hello"} 21162188050 (19.71 GB)
telemt_user_octets_to_client{user="hello"} 444872397120 (414.32 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1582
telemt_user_unique_ips_recent_window{user="hello"} 977
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 135267.1 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10874531
telemt_connections_bad_total 957228
telemt_connections_current 4791
telemt_connections_me_current 4791
telemt_handshake_timeouts_total 306977
telemt_upstream_connect_attempt_total 49582
telemt_upstream_connect_success_total 49502
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2128
telemt_me_reconnect_success_total 1091
telemt_me_reader_eof_total 1074
telemt_me_idle_close_by_peer_total 1073
telemt_me_route_drop_no_conn_total 7139245
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8600780
telemt_me_endpoint_quarantine_total 869
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1010
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
telemt_me_writers_active_current 41
telemt_desync_total 36644
telemt_desync_full_logged_total 11914
telemt_desync_suppressed_total 24730
telemt_desync_frames_bucket_total{bucket="1_2"} 8228
telemt_desync_frames_bucket_total{bucket="3_10"} 14210
telemt_desync_frames_bucket_total{bucket="gt_10"} 14206
telemt_pool_swap_total 146
telemt_pool_force_close_total 4885
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 45212
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41831
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4553
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 332
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40327
telemt_me_writer_teardown_success_total{mode="normal"} 45694
telemt_me_writer_teardown_noop_total 45256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90950
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.559339
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90950
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 948
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 8590203
telemt_user_connections_current{user="hello"} 4791
telemt_user_octets_from_client{user="hello"} 134884738772 (125.62 GB)
telemt_user_octets_to_client{user="hello"} 2679998130244 (2.44 TB)
telemt_user_unique_ips_current{user="hello"} 1725
telemt_user_unique_ips_recent_window{user="hello"} 1281
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 135268.8 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8692314
telemt_connections_bad_total 779226
telemt_connections_current 4576
telemt_connections_me_current 4576
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 269024
telemt_upstream_connect_attempt_total 55759
telemt_upstream_connect_success_total 55238
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 55491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 3026
telemt_me_reconnect_success_total 1185
telemt_me_reader_eof_total 1089
telemt_me_idle_close_by_peer_total 1089
telemt_me_route_drop_no_conn_total 3405432
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6454223
telemt_me_endpoint_quarantine_total 860
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1043
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
telemt_desync_total 29199
telemt_desync_full_logged_total 9892
telemt_desync_suppressed_total 19307
telemt_desync_frames_bucket_total{bucket="1_2"} 7052
telemt_desync_frames_bucket_total{bucket="3_10"} 11308
telemt_desync_frames_bucket_total{bucket="gt_10"} 10839
telemt_pool_swap_total 147
telemt_pool_force_close_total 4461
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 43550
telemt_me_writer_removed_unexpected_total 1105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39089
telemt_me_writer_teardown_success_total{mode="normal"} 44550
telemt_me_writer_teardown_noop_total 43556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 64.260560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1004
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6376159
telemt_user_connections_current{user="hello"} 4576
telemt_user_octets_from_client{user="hello"} 168936601319 (157.33 GB)
telemt_user_octets_to_client{user="hello"} 2967398567326 (2.70 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1658
telemt_user_unique_ips_recent_window{user="hello"} 866
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 135233.1 (37h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8266088
telemt_connections_bad_total 694469
telemt_connections_current 4233
telemt_connections_me_current 4233
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 268018
telemt_upstream_connect_attempt_total 60318
telemt_upstream_connect_success_total 59619
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3511
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 3477211
telemt_me_route_drop_channel_closed_total 227
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6182889
telemt_me_endpoint_quarantine_total 933
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 991
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 28673
telemt_desync_full_logged_total 9749
telemt_desync_suppressed_total 18924
telemt_desync_frames_bucket_total{bucket="1_2"} 6930
telemt_desync_frames_bucket_total{bucket="3_10"} 11021
telemt_desync_frames_bucket_total{bucket="gt_10"} 10722
telemt_pool_swap_total 143
telemt_pool_force_close_total 4358
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 44504
telemt_me_writer_removed_unexpected_total 1383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4175
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40146
telemt_me_writer_teardown_success_total{mode="normal"} 45833
telemt_me_writer_teardown_noop_total 44521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90354
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.363871
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90354
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1295
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 6174937
telemt_user_connections_current{user="hello"} 4233
telemt_user_octets_from_client{user="hello"} 154701289087 (144.08 GB)
telemt_user_octets_to_client{user="hello"} 2692328075659 (2.45 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1611
telemt_user_unique_ips_recent_window{user="hello"} 982
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 5512.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2342795
telemt_connections_bad_total 177069
telemt_connections_current 7243
telemt_connections_me_current 7243
telemt_handshake_timeouts_total 30300
telemt_upstream_connect_attempt_total 8522
telemt_upstream_connect_success_total 8069
telemt_upstream_connect_fail_total 342
telemt_upstream_connect_attempts_per_request{bucket="1"} 8411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 342
telemt_me_keepalive_timeout_total 241
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 127
telemt_me_reader_eof_total 76
telemt_me_idle_close_by_peer_total 76
telemt_me_route_drop_no_conn_total 5219640
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1944409
telemt_me_endpoint_quarantine_total 27
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 45
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 23
telemt_desync_total 3040
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 2276
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1320
telemt_pool_swap_total 4
telemt_pool_force_close_total 156
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 1360
telemt_me_writer_removed_unexpected_total 120
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1262
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1204
telemt_me_writer_teardown_success_total{mode="normal"} 1480
telemt_me_writer_teardown_noop_total 1360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.340911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1950108
telemt_user_connections_current{user="hello"} 7242
telemt_user_octets_from_client{user="hello"} 10462422378 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 56998385047 (53.08 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2401
telemt_user_unique_ips_recent_window{user="hello"} 1543
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 135239.3 (37h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7869688
telemt_connections_bad_total 694369
telemt_connections_current 4047
telemt_connections_me_current 4047
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 161735
telemt_upstream_connect_attempt_total 76664
telemt_upstream_connect_success_total 75831
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 76544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70591
telemt_me_reconnect_success_total 2149
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1889
telemt_me_route_drop_no_conn_total 3286570
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6208536
telemt_me_endpoint_quarantine_total 909
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1017
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
telemt_me_writers_active_current 42
telemt_desync_total 31402
telemt_desync_full_logged_total 10871
telemt_desync_suppressed_total 20531
telemt_desync_frames_bucket_total{bucket="1_2"} 6352
telemt_desync_frames_bucket_total{bucket="3_10"} 12047
telemt_desync_frames_bucket_total{bucket="gt_10"} 13003
telemt_pool_swap_total 140
telemt_pool_force_close_total 4087
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 46883
telemt_me_writer_removed_unexpected_total 1919
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44016
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 519
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42796
telemt_me_writer_teardown_success_total{mode="normal"} 48829
telemt_me_writer_teardown_noop_total 46884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.854444
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 4233
telemt_me_writer_restored_same_endpoint_total 1788
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6203743
telemt_user_connections_current{user="hello"} 4047
telemt_user_octets_from_client{user="hello"} 153195073191 (142.67 GB)
telemt_user_octets_to_client{user="hello"} 2510166006423 (2.28 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1486
telemt_user_unique_ips_recent_window{user="hello"} 1151
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 72075.4 (20h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6753441
telemt_connections_bad_total 254621
telemt_connections_current 5322
telemt_connections_me_current 5322
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2736619
telemt_upstream_connect_attempt_total 37815
telemt_upstream_connect_success_total 37546
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 37808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 47572
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 933
telemt_me_idle_close_by_peer_total 933
telemt_me_route_drop_no_conn_total 1970036
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3363509
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 22
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 18136
telemt_desync_full_logged_total 6087
telemt_desync_suppressed_total 12049
telemt_desync_frames_bucket_total{bucket="1_2"} 3666
telemt_desync_frames_bucket_total{bucket="3_10"} 6950
telemt_desync_frames_bucket_total{bucket="gt_10"} 7520
telemt_pool_swap_total 76
telemt_pool_force_close_total 2310
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 25692
telemt_me_writer_removed_unexpected_total 1003
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24475
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23382
telemt_me_writer_teardown_success_total{mode="normal"} 26718
telemt_me_writer_teardown_noop_total 25698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52416
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.908078
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52416
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 2692
telemt_me_writer_restored_same_endpoint_total 1129
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3363336
telemt_user_connections_current{user="hello"} 5322
telemt_user_octets_from_client{user="hello"} 81730169452 (76.12 GB)
telemt_user_octets_to_client{user="hello"} 1399672812046 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2018
telemt_user_unique_ips_recent_window{user="hello"} 872
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53046.0 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524592
telemt_connections_bad_total 3771
telemt_connections_current 1126
telemt_connections_me_current 1126
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9686
telemt_upstream_connect_attempt_total 27846
telemt_upstream_connect_success_total 27782
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1134
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 457
telemt_me_idle_close_by_peer_total 457
telemt_me_route_drop_no_conn_total 170869
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474347
telemt_me_endpoint_quarantine_total 484
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 452
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
telemt_me_writers_active_current 43
telemt_desync_total 2306
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1645
telemt_desync_frames_bucket_total{bucket="1_2"} 683
telemt_desync_frames_bucket_total{bucket="3_10"} 898
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 56
telemt_pool_force_close_total 1327
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 22559
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1650
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21366
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21232
telemt_me_writer_teardown_success_total{mode="normal"} 23016
telemt_me_writer_teardown_noop_total 22559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45575
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.208264
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45575
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 476397
telemt_user_connections_current{user="hello"} 1126
telemt_user_octets_from_client{user="hello"} 9459957133 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 231462609395 (215.57 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 135243.7 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9659609
telemt_connections_bad_total 1125254
telemt_connections_current 5790
telemt_connections_me_current 5790
telemt_handshake_timeouts_total 261210
telemt_upstream_connect_attempt_total 52100
telemt_upstream_connect_success_total 51902
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 52054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1983
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1040
telemt_me_idle_close_by_peer_total 1040
telemt_me_route_drop_no_conn_total 2753173
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7184642
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1024
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
telemt_me_writers_active_current 46
telemt_desync_total 29156
telemt_desync_full_logged_total 9556
telemt_desync_suppressed_total 19600
telemt_desync_frames_bucket_total{bucket="1_2"} 7207
telemt_desync_frames_bucket_total{bucket="3_10"} 10649
telemt_desync_frames_bucket_total{bucket="gt_10"} 11300
telemt_pool_swap_total 150
telemt_pool_force_close_total 4056
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 46991
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 114
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42935
telemt_me_writer_teardown_success_total{mode="normal"} 48022
telemt_me_writer_teardown_noop_total 46993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95015
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.027792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95015
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 940
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7156940
telemt_user_connections_current{user="hello"} 5790
telemt_user_octets_from_client{user="hello"} 138447461848 (128.94 GB)
telemt_user_octets_to_client{user="hello"} 3340371076124 (3.04 TB)
telemt_user_unique_ips_current{user="hello"} 1978
telemt_user_unique_ips_recent_window{user="hello"} 1170
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 135240.4 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8382707
telemt_connections_bad_total 931968
telemt_connections_current 4733
telemt_connections_me_current 4733
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 218110
telemt_upstream_connect_attempt_total 76599
telemt_upstream_connect_success_total 76056
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 76530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_reconnect_attempts_total 6568
telemt_me_reconnect_success_total 1532
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_seq_mismatch_total 64
telemt_me_route_drop_no_conn_total 2974237
telemt_me_route_drop_channel_closed_total 263
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6406055
telemt_me_endpoint_quarantine_total 1053
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1025
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
telemt_desync_total 28209
telemt_desync_full_logged_total 9325
telemt_desync_suppressed_total 18884
telemt_desync_frames_bucket_total{bucket="1_2"} 6934
telemt_desync_frames_bucket_total{bucket="3_10"} 10392
telemt_desync_frames_bucket_total{bucket="gt_10"} 10883
telemt_pool_swap_total 147
telemt_pool_force_close_total 3985
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 45671
telemt_me_writer_removed_unexpected_total 1379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4437
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41686
telemt_me_writer_teardown_success_total{mode="normal"} 47112
telemt_me_writer_teardown_noop_total 45675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92787
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.545806
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92787
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 88
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6414235
telemt_user_connections_current{user="hello"} 4733
telemt_user_octets_from_client{user="hello"} 116716601265 (108.70 GB)
telemt_user_octets_to_client{user="hello"} 2718013067511 (2.47 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1720
telemt_user_unique_ips_recent_window{user="hello"} 1171
```