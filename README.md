# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

## rdp-onedash.ru
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

## 4vps.su
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

# Server Metrics 2026-03-20 16:04:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6512.6 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318254
telemt_connections_bad_total 14451
telemt_connections_current 1481
telemt_connections_me_current 1481
telemt_handshake_timeouts_total 6604
telemt_upstream_connect_attempt_total 2624
telemt_upstream_connect_success_total 2612
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 503
telemt_me_reconnect_success_total 201
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 337916
telemt_me_route_drop_channel_closed_total 138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279749
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_shadow_rotate_total 52
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
telemt_me_writers_active_current 44
telemt_desync_total 1014
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 694
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 438
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 5
telemt_pool_force_close_total 195
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 2178
telemt_me_writer_removed_unexpected_total 212
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1983
telemt_me_writer_teardown_success_total{mode="normal"} 2381
telemt_me_writer_teardown_noop_total 2179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.850125
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 194
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 279175
telemt_user_connections_current{user="hello"} 1481
telemt_user_octets_from_client{user="hello"} 2766589320 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 54547549140 (50.80 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 6522.1 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809909
telemt_connections_bad_total 44930
telemt_connections_current 3617
telemt_connections_me_current 3617
telemt_handshake_timeouts_total 12448
telemt_upstream_connect_attempt_total 2193
telemt_upstream_connect_success_total 2171
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 153
telemt_me_reconnect_success_total 90
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 317353
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612085
telemt_me_endpoint_quarantine_total 31
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 51
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
telemt_desync_total 2047
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1337
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 6
telemt_pool_force_close_total 265
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 1874
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1609
telemt_me_writer_teardown_success_total{mode="normal"} 1921
telemt_me_writer_teardown_noop_total 1880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3801
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.876680
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3801
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 611406
telemt_user_connections_current{user="hello"} 3617
telemt_user_octets_from_client{user="hello"} 7437225900 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 181427759448 (168.97 GB)
telemt_user_unique_ips_current{user="hello"} 1196
telemt_user_unique_ips_recent_window{user="hello"} 1254
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 6515.5 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577904
telemt_connections_bad_total 34177
telemt_connections_current 4760
telemt_connections_me_current 4760
telemt_handshake_timeouts_total 8601
telemt_upstream_connect_attempt_total 2764
telemt_upstream_connect_success_total 2696
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 2761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 337
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 187
telemt_me_idle_close_by_peer_total 187
telemt_me_route_drop_no_conn_total 223159
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489013
telemt_me_endpoint_quarantine_total 44
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
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
telemt_me_writers_active_current 86
telemt_me_writers_warm_current 7
telemt_desync_total 1595
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 4
telemt_pool_force_close_total 236
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 2259
telemt_me_writer_removed_unexpected_total 184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 337
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2023
telemt_me_writer_teardown_success_total{mode="normal"} 2408
telemt_me_writer_teardown_noop_total 2259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4667
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.640017
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4667
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 209
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 488638
telemt_user_connections_current{user="hello"} 4760
telemt_user_octets_from_client{user="hello"} 8508465956 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 170827177648 (159.10 GB)
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 931
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 20573.8 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3609885
telemt_connections_bad_total 363453
telemt_connections_current 5952
telemt_connections_me_current 5952
telemt_handshake_timeouts_total 65991
telemt_upstream_connect_attempt_total 6694
telemt_upstream_connect_success_total 6654
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 659
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_route_drop_no_conn_total 2348096
telemt_me_route_drop_channel_closed_total 147
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2869908
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 87
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 132
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
telemt_me_writers_active_current 44
telemt_desync_total 7716
telemt_desync_full_logged_total 2208
telemt_desync_suppressed_total 5508
telemt_desync_frames_bucket_total{bucket="1_2"} 1929
telemt_desync_frames_bucket_total{bucket="3_10"} 2984
telemt_desync_frames_bucket_total{bucket="gt_10"} 2803
telemt_pool_swap_total 15
telemt_pool_force_close_total 800
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 5734
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 337
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4934
telemt_me_writer_teardown_success_total{mode="normal"} 6079
telemt_me_writer_teardown_noop_total 5744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.687624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2866757
telemt_user_connections_current{user="hello"} 5952
telemt_user_octets_from_client{user="hello"} 31605366048 (29.43 GB)
telemt_user_octets_to_client{user="hello"} 770211938104 (717.32 GB)
telemt_user_unique_ips_current{user="hello"} 1887
telemt_user_unique_ips_recent_window{user="hello"} 799
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 6515.0 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2466156
telemt_connections_bad_total 56496
telemt_connections_current 5845
telemt_connections_me_current 5845
telemt_handshake_timeouts_total 28109
telemt_upstream_connect_attempt_total 8396
telemt_upstream_connect_success_total 7979
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 8275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 467
telemt_me_reconnect_success_total 257
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 4979017
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2235283
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 52
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
telemt_me_writers_active_current 75
telemt_me_writers_warm_current 9
telemt_desync_total 2880
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 2060
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 1292
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 4
telemt_pool_force_close_total 183
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 1860
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1677
telemt_me_writer_teardown_success_total{mode="normal"} 2128
telemt_me_writer_teardown_noop_total 1861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3989
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.509005
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3989
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2240340
telemt_user_connections_current{user="hello"} 5845
telemt_user_octets_from_client{user="hello"} 9624747940 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 70323801698 (65.49 GB)
telemt_user_msgs_from_client{user="hello"} 4517
telemt_user_msgs_to_client{user="hello"} 3964
telemt_user_unique_ips_current{user="hello"} 1829
telemt_user_unique_ips_recent_window{user="hello"} 1112
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 6519.6 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2121697
telemt_connections_bad_total 145405
telemt_connections_current 6682
telemt_connections_me_current 6682
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 19561
telemt_upstream_connect_attempt_total 19056
telemt_upstream_connect_success_total 19049
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 195
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 3530906
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1798418
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 48
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
telemt_me_writers_active_current 44
telemt_desync_total 2886
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 2044
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 1246
telemt_desync_frames_bucket_total{bucket="gt_10"} 909
telemt_pool_swap_total 7
telemt_pool_force_close_total 211
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 1496
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 177
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1285
telemt_me_writer_teardown_success_total{mode="normal"} 1521
telemt_me_writer_teardown_noop_total 1500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 114.089751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1812267
telemt_user_connections_current{user="hello"} 6682
telemt_user_octets_from_client{user="hello"} 13882998440 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 134363531827 (125.14 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1996
telemt_user_unique_ips_recent_window{user="hello"} 1276
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5943.7 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119522
telemt_connections_bad_total 1246
telemt_connections_current 707
telemt_connections_me_current 707
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 2128
telemt_upstream_connect_attempt_total 3864
telemt_upstream_connect_success_total 3861
telemt_upstream_connect_attempts_per_request{bucket="1"} 3861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 212
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 98508
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106495
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 331
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 6
telemt_pool_force_close_total 165
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 45
telemt_me_draining_writers_reap_progress_total 1870
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 201
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1705
telemt_me_writer_teardown_success_total{mode="normal"} 1904
telemt_me_writer_teardown_noop_total 1871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3775
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.325697
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3775
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 45
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 107505
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 1123161718 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 20332695541 (18.94 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 6517.5 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134813
telemt_connections_bad_total 71950
telemt_connections_current 7530
telemt_connections_me_current 7530
telemt_handshake_timeouts_total 39309
telemt_upstream_connect_attempt_total 1980
telemt_upstream_connect_success_total 1978
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 127
telemt_me_reconnect_success_total 70
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 518243
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959431
telemt_me_endpoint_quarantine_total 30
telemt_me_single_endpoint_shadow_rotate_total 45
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
telemt_me_writers_active_current 46
telemt_desync_total 3511
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 2531
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1298
telemt_desync_frames_bucket_total{bucket="gt_10"} 1308
telemt_pool_swap_total 6
telemt_pool_force_close_total 229
telemt_me_writer_close_signal_drop_total 27
telemt_me_draining_writers_reap_progress_total 1659
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1430
telemt_me_writer_teardown_success_total{mode="normal"} 1733
telemt_me_writer_teardown_noop_total 1660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3393
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.013802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3393
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 27
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 958436
telemt_user_connections_current{user="hello"} 7530
telemt_user_octets_from_client{user="hello"} 12927218488 (12.04 GB)
telemt_user_octets_to_client{user="hello"} 304095345064 (283.21 GB)
telemt_user_unique_ips_current{user="hello"} 2129
telemt_user_unique_ips_recent_window{user="hello"} 2060
```