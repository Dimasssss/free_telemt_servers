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

# Server Metrics 2026-03-21 21:55:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 2970.8 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61060
telemt_connections_bad_total 4155
telemt_connections_current 701
telemt_connections_me_current 701
telemt_handshake_timeouts_total 2616
telemt_upstream_connect_attempt_total 1245
telemt_upstream_connect_success_total 1244
telemt_upstream_connect_attempts_per_request{bucket="1"} 1244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 13902
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49301
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 43
telemt_desync_total 332
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 3
telemt_pool_force_close_total 76
telemt_me_writer_close_signal_drop_total 8
telemt_me_draining_writers_reap_progress_total 1077
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1024
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1001
telemt_me_writer_teardown_success_total{mode="normal"} 1088
telemt_me_writer_teardown_noop_total 1077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.981481
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 8
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 49255
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 672539944 (641.38 MB)
telemt_user_octets_to_client{user="hello"} 15820506824 (14.73 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 16337.5 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573148
telemt_connections_bad_total 26921
telemt_connections_current 1161
telemt_connections_me_current 1161
telemt_handshake_timeouts_total 20432
telemt_upstream_connect_attempt_total 6578
telemt_upstream_connect_success_total 6447
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 6563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_reconnect_attempts_total 588
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 304486
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464097
telemt_me_endpoint_quarantine_total 136
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 129
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
telemt_me_writers_active_current 42
telemt_desync_total 2079
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 901
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 18
telemt_pool_force_close_total 502
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 5725
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5393
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 495
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5223
telemt_me_writer_teardown_success_total{mode="normal"} 5892
telemt_me_writer_teardown_noop_total 5725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.907524
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 144
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 463509
telemt_user_connections_current{user="hello"} 1161
telemt_user_octets_from_client{user="hello"} 8125509240 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 153434147768 (142.90 GB)
telemt_user_unique_ips_current{user="hello"} 737
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 91197.5 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7170736
telemt_connections_bad_total 553601
telemt_connections_current 2121
telemt_connections_me_current 2121
telemt_handshake_timeouts_total 223916
telemt_upstream_connect_attempt_total 32799
telemt_upstream_connect_success_total 32734
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1439
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 4439794
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5863904
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 675
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 24676
telemt_desync_full_logged_total 8139
telemt_desync_suppressed_total 16537
telemt_desync_frames_bucket_total{bucket="1_2"} 5295
telemt_desync_frames_bucket_total{bucket="3_10"} 9689
telemt_desync_frames_bucket_total{bucket="gt_10"} 9692
telemt_pool_swap_total 98
telemt_pool_force_close_total 3315
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 545
telemt_me_draining_writers_reap_progress_total 29891
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3077
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26576
telemt_me_writer_teardown_success_total{mode="normal"} 30160
telemt_me_writer_teardown_noop_total 29935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 147.745053
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 545
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 618
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5856767
telemt_user_connections_current{user="hello"} 2121
telemt_user_octets_from_client{user="hello"} 100713332992 (93.80 GB)
telemt_user_octets_to_client{user="hello"} 1884469111488 (1.71 TB)
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 91198.7 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5864808
telemt_connections_bad_total 571032
telemt_connections_current 2186
telemt_connections_me_current 2186
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 191416
telemt_upstream_connect_attempt_total 36779
telemt_upstream_connect_success_total 36448
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 36620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1719
telemt_me_reconnect_success_total 724
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 2035483
telemt_me_route_drop_channel_closed_total 234
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4372287
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 697
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
telemt_me_writers_active_current 43
telemt_desync_total 21095
telemt_desync_full_logged_total 7034
telemt_desync_suppressed_total 14061
telemt_desync_frames_bucket_total{bucket="1_2"} 5107
telemt_desync_frames_bucket_total{bucket="3_10"} 8172
telemt_desync_frames_bucket_total{bucket="gt_10"} 7816
telemt_pool_swap_total 100
telemt_pool_force_close_total 3037
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 339
telemt_me_draining_writers_reap_progress_total 28513
telemt_me_writer_removed_unexpected_total 677
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2462
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25476
telemt_me_writer_teardown_success_total{mode="normal"} 29121
telemt_me_writer_teardown_noop_total 28519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.423607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 339
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4350863
telemt_user_connections_current{user="hello"} 2186
telemt_user_octets_from_client{user="hello"} 133730322969 (124.55 GB)
telemt_user_octets_to_client{user="hello"} 2017608755319 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 946
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 91162.0 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5791283
telemt_connections_bad_total 528515
telemt_connections_current 2052
telemt_connections_me_current 2052
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 180006
telemt_upstream_connect_attempt_total 43193
telemt_upstream_connect_success_total 42906
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1755
telemt_me_reconnect_success_total 789
telemt_me_reader_eof_total 734
telemt_me_idle_close_by_peer_total 734
telemt_me_route_drop_no_conn_total 2054598
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4342408
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 681
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 20850
telemt_desync_full_logged_total 6841
telemt_desync_suppressed_total 14009
telemt_desync_frames_bucket_total{bucket="1_2"} 5173
telemt_desync_frames_bucket_total{bucket="3_10"} 7909
telemt_desync_frames_bucket_total{bucket="gt_10"} 7768
telemt_pool_swap_total 98
telemt_pool_force_close_total 2913
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 29933
telemt_me_writer_removed_unexpected_total 703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2548
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28092
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2698
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27020
telemt_me_writer_teardown_success_total{mode="normal"} 30640
telemt_me_writer_teardown_noop_total 29943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60583
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.766741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60583
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 683
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 4344216
telemt_user_connections_current{user="hello"} 2052
telemt_user_octets_from_client{user="hello"} 127568740607 (118.81 GB)
telemt_user_octets_to_client{user="hello"} 1982862063099 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 866
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 91201.5 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19544015
telemt_connections_bad_total 1341105
telemt_connections_current 2661
telemt_connections_me_current 2661
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 552092
telemt_upstream_connect_attempt_total 182866
telemt_upstream_connect_success_total 165559
telemt_upstream_connect_fail_total 15820
telemt_upstream_connect_attempts_per_request{bucket="1"} 181379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15820
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59724
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 39374943
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16010704
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 665
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 707
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 30472
telemt_desync_full_logged_total 9009
telemt_desync_suppressed_total 21463
telemt_desync_frames_bucket_total{bucket="1_2"} 6669
telemt_desync_frames_bucket_total{bucket="3_10"} 13515
telemt_desync_frames_bucket_total{bucket="gt_10"} 10288
telemt_pool_swap_total 93
telemt_pool_force_close_total 3150
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 28167
telemt_me_writer_removed_unexpected_total 1836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3846
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25884
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2642
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25017
telemt_me_writer_teardown_success_total{mode="normal"} 29730
telemt_me_writer_teardown_noop_total 28193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57923
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 207.252018
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57923
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16135720
telemt_user_connections_current{user="hello"} 2661
telemt_user_octets_from_client{user="hello"} 164918611922 (153.59 GB)
telemt_user_octets_to_client{user="hello"} 1028266131590 (957.65 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 91168.8 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5631147
telemt_connections_bad_total 530866
telemt_connections_current 1523
telemt_connections_me_current 1523
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 116048
telemt_upstream_connect_attempt_total 50562
telemt_upstream_connect_success_total 50034
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 50476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_reconnect_attempts_total 11320
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 1231
telemt_me_idle_close_by_peer_total 1231
telemt_me_route_drop_no_conn_total 2316303
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4379849
telemt_me_endpoint_quarantine_total 566
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 680
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
telemt_desync_total 21991
telemt_desync_full_logged_total 7626
telemt_desync_suppressed_total 14365
telemt_desync_frames_bucket_total{bucket="1_2"} 4198
telemt_desync_frames_bucket_total{bucket="3_10"} 8541
telemt_desync_frames_bucket_total{bucket="gt_10"} 9252
telemt_pool_swap_total 93
telemt_pool_force_close_total 2729
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 354
telemt_me_draining_writers_reap_progress_total 30854
telemt_me_writer_removed_unexpected_total 1222
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28928
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28125
telemt_me_writer_teardown_success_total{mode="normal"} 32090
telemt_me_writer_teardown_noop_total 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62945
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.613084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62945
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 354
telemt_me_refill_failed_total 601
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4373226
telemt_user_connections_current{user="hello"} 1523
telemt_user_octets_from_client{user="hello"} 116414798616 (108.42 GB)
telemt_user_octets_to_client{user="hello"} 1774757905142 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 28004.5 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3419785
telemt_connections_bad_total 122802
telemt_connections_current 2632
telemt_connections_me_current 2632
telemt_handshake_timeouts_total 1444242
telemt_upstream_connect_attempt_total 9402
telemt_upstream_connect_success_total 9281
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 9396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 2298
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 234
telemt_me_idle_close_by_peer_total 234
telemt_me_route_drop_no_conn_total 960667
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1637836
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 206
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 63
telemt_me_writers_warm_current 36
telemt_desync_total 9035
telemt_desync_full_logged_total 3026
telemt_desync_suppressed_total 6009
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 3451
telemt_desync_frames_bucket_total{bucket="gt_10"} 3958
telemt_pool_swap_total 29
telemt_pool_force_close_total 932
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 8156
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 742
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7680
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7224
telemt_me_writer_teardown_success_total{mode="normal"} 8422
telemt_me_writer_teardown_noop_total 8157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.469760
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1633088
telemt_user_connections_current{user="hello"} 2632
telemt_user_octets_from_client{user="hello"} 47411243856 (44.16 GB)
telemt_user_octets_to_client{user="hello"} 701497066936 (653.32 GB)
telemt_user_unique_ips_current{user="hello"} 1177
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 8976.1 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114592
telemt_connections_bad_total 1219
telemt_connections_current 518
telemt_connections_me_current 518
telemt_handshake_timeouts_total 3194
telemt_upstream_connect_attempt_total 3793
telemt_upstream_connect_success_total 3782
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 32400
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98929
telemt_me_endpoint_quarantine_total 61
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 862
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 9
telemt_pool_force_close_total 240
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 3329
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3089
telemt_me_writer_teardown_success_total{mode="normal"} 3372
telemt_me_writer_teardown_noop_total 3329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6701
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.521226
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6701
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 98789
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 2147884528 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 62819193384 (58.50 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 91173.6 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6705572
telemt_connections_bad_total 677258
telemt_connections_current 2649
telemt_connections_me_current 2649
telemt_handshake_timeouts_total 193522
telemt_upstream_connect_attempt_total 34513
telemt_upstream_connect_success_total 34375
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 1418
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 698
telemt_me_route_drop_no_conn_total 2050684
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5128873
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 696
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
telemt_me_writers_active_current 44
telemt_desync_total 19642
telemt_desync_full_logged_total 6552
telemt_desync_suppressed_total 13090
telemt_desync_frames_bucket_total{bucket="1_2"} 4783
telemt_desync_frames_bucket_total{bucket="3_10"} 7169
telemt_desync_frames_bucket_total{bucket="gt_10"} 7690
telemt_pool_swap_total 101
telemt_pool_force_close_total 2764
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 31020
telemt_me_writer_removed_unexpected_total 679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29196
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28256
telemt_me_writer_teardown_success_total{mode="normal"} 31708
telemt_me_writer_teardown_noop_total 31022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62730
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.145047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62730
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 646
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5104399
telemt_user_connections_current{user="hello"} 2649
telemt_user_octets_from_client{user="hello"} 103155963072 (96.07 GB)
telemt_user_octets_to_client{user="hello"} 2391895238276 (2.18 TB)
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 91169.7 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5711459
telemt_connections_bad_total 541877
telemt_connections_current 2364
telemt_connections_me_current 2364
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 162014
telemt_upstream_connect_attempt_total 50700
telemt_upstream_connect_success_total 50318
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 50641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 5206
telemt_me_reconnect_success_total 1031
telemt_me_reader_eof_total 906
telemt_me_idle_close_by_peer_total 906
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2104005
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4493893
telemt_me_endpoint_quarantine_total 718
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 692
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
telemt_me_writers_active_current 51
telemt_desync_total 18272
telemt_desync_full_logged_total 6174
telemt_desync_suppressed_total 12098
telemt_desync_frames_bucket_total{bucket="1_2"} 4531
telemt_desync_frames_bucket_total{bucket="3_10"} 6679
telemt_desync_frames_bucket_total{bucket="gt_10"} 7062
telemt_pool_swap_total 99
telemt_pool_force_close_total 2713
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 30017
telemt_me_writer_removed_unexpected_total 917
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3015
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27961
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2500
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27304
telemt_me_writer_teardown_success_total{mode="normal"} 30976
telemt_me_writer_teardown_noop_total 30021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60997
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.215629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60997
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 794
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 4497548
telemt_user_connections_current{user="hello"} 2364
telemt_user_octets_from_client{user="hello"} 85609099945 (79.73 GB)
telemt_user_octets_to_client{user="hello"} 1919351686448 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 940
telemt_user_unique_ips_recent_window{user="hello"} 277
```