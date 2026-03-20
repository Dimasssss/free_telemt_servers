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

# Server Metrics 2026-03-20 15:48:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 5582.3 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274619
telemt_connections_bad_total 12198
telemt_connections_current 1554
telemt_connections_me_current 1554
telemt_handshake_timeouts_total 6059
telemt_upstream_connect_attempt_total 2329
telemt_upstream_connect_success_total 2319
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 465
telemt_me_reconnect_success_total 196
telemt_me_reader_eof_total 206
telemt_me_idle_close_by_peer_total 206
telemt_me_route_drop_no_conn_total 305616
telemt_me_route_drop_channel_closed_total 110
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241625
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_shadow_rotate_total 45
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
telemt_me_writers_active_current 43
telemt_desync_total 921
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 4
telemt_pool_force_close_total 137
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 1891
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1772
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1754
telemt_me_writer_teardown_success_total{mode="normal"} 2088
telemt_me_writer_teardown_noop_total 1891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3979
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.873586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3979
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 189
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 241442
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 2496388784 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 45064915816 (41.97 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5591.6 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698585
telemt_connections_bad_total 41312
telemt_connections_current 4175
telemt_connections_me_current 4175
telemt_handshake_timeouts_total 10619
telemt_upstream_connect_attempt_total 1934
telemt_upstream_connect_success_total 1912
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 147
telemt_me_reconnect_success_total 85
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 257472
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521431
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 44
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
telemt_desync_total 1690
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 5
telemt_pool_force_close_total 229
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 1651
telemt_me_writer_removed_unexpected_total 70
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1503
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1422
telemt_me_writer_teardown_success_total{mode="normal"} 1693
telemt_me_writer_teardown_noop_total 1657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.658180
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 520971
telemt_user_connections_current{user="hello"} 4175
telemt_user_octets_from_client{user="hello"} 6404235200 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 154134608852 (143.55 GB)
telemt_user_unique_ips_current{user="hello"} 1342
telemt_user_unique_ips_recent_window{user="hello"} 686
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 5585.9 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490643
telemt_connections_bad_total 30940
telemt_connections_current 3704
telemt_connections_me_current 3704
telemt_handshake_timeouts_total 6240
telemt_upstream_connect_attempt_total 2407
telemt_upstream_connect_success_total 2351
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 2404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 297
telemt_me_reconnect_success_total 185
telemt_me_reader_eof_total 148
telemt_me_idle_close_by_peer_total 148
telemt_me_route_drop_no_conn_total 193473
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419985
telemt_me_endpoint_quarantine_total 43
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 44
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
telemt_me_writers_active_current 51
telemt_desync_total 1191
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 4
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 1992
telemt_me_writer_removed_unexpected_total 145
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1816
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 99
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1776
telemt_me_writer_teardown_success_total{mode="normal"} 2102
telemt_me_writer_teardown_noop_total 1992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4094
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.596255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4094
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 171
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 419643
telemt_user_connections_current{user="hello"} 3704
telemt_user_octets_from_client{user="hello"} 7438430164 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 144480452148 (134.56 GB)
telemt_user_unique_ips_current{user="hello"} 1283
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 19643.6 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3478756
telemt_connections_bad_total 347760
telemt_connections_current 5521
telemt_connections_me_current 5521
telemt_handshake_timeouts_total 63492
telemt_upstream_connect_attempt_total 6446
telemt_upstream_connect_success_total 6409
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 651
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 2300231
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2767353
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 85
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 124
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
telemt_desync_total 7398
telemt_desync_full_logged_total 2110
telemt_desync_suppressed_total 5288
telemt_desync_frames_bucket_total{bucket="1_2"} 1828
telemt_desync_frames_bucket_total{bucket="3_10"} 2866
telemt_desync_frames_bucket_total{bucket="gt_10"} 2704
telemt_pool_swap_total 14
telemt_pool_force_close_total 764
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 5513
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5093
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4749
telemt_me_writer_teardown_success_total{mode="normal"} 5850
telemt_me_writer_teardown_noop_total 5523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11373
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.907703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11373
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2764318
telemt_user_connections_current{user="hello"} 5521
telemt_user_octets_from_client{user="hello"} 30023894804 (27.96 GB)
telemt_user_octets_to_client{user="hello"} 735144891628 (684.66 GB)
telemt_user_unique_ips_current{user="hello"} 1823
telemt_user_unique_ips_recent_window{user="hello"} 729
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 5584.2 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2130735
telemt_connections_bad_total 45576
telemt_connections_current 5595
telemt_connections_me_current 5595
telemt_handshake_timeouts_total 22283
telemt_upstream_connect_attempt_total 8088
telemt_upstream_connect_success_total 7700
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 7983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 385
telemt_me_reconnect_success_total 228
telemt_me_reader_eof_total 189
telemt_me_idle_close_by_peer_total 189
telemt_me_route_drop_no_conn_total 4312838
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1933398
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 46
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
telemt_me_writers_active_current 49
telemt_desync_total 2569
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1873
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 864
telemt_pool_swap_total 4
telemt_pool_force_close_total 155
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 1644
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 350
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1489
telemt_me_writer_teardown_success_total{mode="normal"} 1874
telemt_me_writer_teardown_noop_total 1645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3519
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.191526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3519
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 190
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1938603
telemt_user_connections_current{user="hello"} 5595
telemt_user_octets_from_client{user="hello"} 7373551416 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 60690663034 (56.52 GB)
telemt_user_msgs_from_client{user="hello"} 4517
telemt_user_msgs_to_client{user="hello"} 3964
telemt_user_unique_ips_current{user="hello"} 1745
telemt_user_unique_ips_recent_window{user="hello"} 920
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 5589.4 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833882
telemt_connections_bad_total 126123
telemt_connections_current 5903
telemt_connections_me_current 5903
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 17406
telemt_upstream_connect_attempt_total 18819
telemt_upstream_connect_success_total 18812
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 191
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 53
telemt_me_idle_close_by_peer_total 53
telemt_me_route_drop_no_conn_total 3086049
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1549017
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
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
telemt_me_writers_active_current 43
telemt_desync_total 2493
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1783
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 810
telemt_pool_swap_total 6
telemt_pool_force_close_total 148
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 1268
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1143
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1120
telemt_me_writer_teardown_success_total{mode="normal"} 1288
telemt_me_writer_teardown_noop_total 1272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 113.323515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 1563729
telemt_user_connections_current{user="hello"} 5903
telemt_user_octets_from_client{user="hello"} 11355943056 (10.58 GB)
telemt_user_octets_to_client{user="hello"} 115208375619 (107.30 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1942
telemt_user_unique_ips_recent_window{user="hello"} 864
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5012.1 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100242
telemt_connections_bad_total 1067
telemt_connections_current 718
telemt_connections_me_current 718
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 1535
telemt_upstream_connect_attempt_total 3503
telemt_upstream_connect_success_total 3500
telemt_upstream_connect_attempts_per_request{bucket="1"} 3500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 187
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 84962
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91203
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 40
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
telemt_desync_total 244
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 5
telemt_pool_force_close_total 121
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 1550
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1418
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1429
telemt_me_writer_teardown_success_total{mode="normal"} 1591
telemt_me_writer_teardown_noop_total 1550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3141
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.984984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3141
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 92228
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 939823774 (896.29 MB)
telemt_user_octets_to_client{user="hello"} 17732066869 (16.51 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 5587.3 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966080
telemt_connections_bad_total 67032
telemt_connections_current 5589
telemt_connections_me_current 5589
telemt_handshake_timeouts_total 32810
telemt_upstream_connect_attempt_total 1720
telemt_upstream_connect_success_total 1718
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 64
telemt_me_idle_close_by_peer_total 64
telemt_me_route_drop_no_conn_total 409989
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 809484
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_shadow_rotate_total 38
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
telemt_desync_total 2896
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 2065
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 1123
telemt_desync_frames_bucket_total{bucket="gt_10"} 1137
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 1436
telemt_me_writer_removed_unexpected_total 64
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1337
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1240
telemt_me_writer_teardown_success_total{mode="normal"} 1502
telemt_me_writer_teardown_noop_total 1437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2939
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.964956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2939
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 808781
telemt_user_connections_current{user="hello"} 5590
telemt_user_octets_from_client{user="hello"} 11061746564 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 264536256932 (246.37 GB)
telemt_user_unique_ips_current{user="hello"} 1629
telemt_user_unique_ips_recent_window{user="hello"} 1295
```