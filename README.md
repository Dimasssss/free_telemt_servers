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

# Server Metrics 2026-03-22 04:12:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 25592.2 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403190
telemt_connections_bad_total 25436
telemt_connections_current 925
telemt_connections_me_current 925
telemt_handshake_timeouts_total 22010
telemt_upstream_connect_attempt_total 10755
telemt_upstream_connect_success_total 10754
telemt_upstream_connect_attempts_per_request{bucket="1"} 10754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 293
telemt_me_reconnect_success_total 166
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 82723
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334228
telemt_me_endpoint_quarantine_total 205
telemt_me_single_endpoint_shadow_rotate_total 216
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
telemt_me_writers_active_current 45
telemt_desync_total 3022
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 2196
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1140
telemt_desync_frames_bucket_total{bucket="gt_10"} 836
telemt_pool_swap_total 28
telemt_pool_force_close_total 734
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 9722
telemt_me_writer_removed_unexpected_total 160
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 729
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8988
telemt_me_writer_teardown_success_total{mode="normal"} 9874
telemt_me_writer_teardown_noop_total 9723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19597
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.581629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19597
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 149
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 333283
telemt_user_connections_current{user="hello"} 925
telemt_user_octets_from_client{user="hello"} 4208743260 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 115770208788 (107.82 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38958.2 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864413
telemt_connections_bad_total 57607
telemt_connections_current 592
telemt_connections_me_current 592
telemt_handshake_timeouts_total 31058
telemt_upstream_connect_attempt_total 18266
telemt_upstream_connect_success_total 17981
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 18239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 1505
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 493
telemt_me_idle_close_by_peer_total 493
telemt_me_route_drop_no_conn_total 354530
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684869
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 316
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2931
telemt_desync_full_logged_total 1678
telemt_desync_suppressed_total 1253
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1128
telemt_desync_frames_bucket_total{bucket="gt_10"} 1186
telemt_pool_swap_total 42
telemt_pool_force_close_total 1124
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 16219
telemt_me_writer_removed_unexpected_total 469
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15351
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15095
telemt_me_writer_teardown_success_total{mode="normal"} 16699
telemt_me_writer_teardown_noop_total 16219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.906582
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 414
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 683819
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 11046793752 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 246240856636 (229.33 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 113818.1 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7954610
telemt_connections_bad_total 662257
telemt_connections_current 2289
telemt_connections_me_current 2289
telemt_handshake_timeouts_total 261598
telemt_upstream_connect_attempt_total 42516
telemt_upstream_connect_success_total 42437
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 42445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1628
telemt_me_reconnect_success_total 846
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 4573670
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6425338
telemt_me_endpoint_quarantine_total 737
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 852
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
telemt_me_writers_active_current 44
telemt_desync_total 26939
telemt_desync_full_logged_total 8947
telemt_desync_suppressed_total 17992
telemt_desync_frames_bucket_total{bucket="1_2"} 5825
telemt_desync_frames_bucket_total{bucket="3_10"} 10529
telemt_desync_frames_bucket_total{bucket="gt_10"} 10585
telemt_pool_swap_total 123
telemt_pool_force_close_total 4046
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 38793
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3225
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3806
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34747
telemt_me_writer_teardown_success_total{mode="normal"} 39151
telemt_me_writer_teardown_noop_total 38837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77988
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.443971
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77988
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 754
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6417138
telemt_user_connections_current{user="hello"} 2289
telemt_user_octets_from_client{user="hello"} 109115904992 (101.62 GB)
telemt_user_octets_to_client{user="hello"} 2154630355732 (1.96 TB)
telemt_user_unique_ips_current{user="hello"} 1041
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 113819.4 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6580404
telemt_connections_bad_total 594051
telemt_connections_current 2253
telemt_connections_me_current 2253
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 218455
telemt_upstream_connect_attempt_total 46457
telemt_upstream_connect_success_total 46061
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 46260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1973
telemt_me_reconnect_success_total 902
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 2288033
telemt_me_route_drop_channel_closed_total 278
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4910203
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 879
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
telemt_desync_total 22988
telemt_desync_full_logged_total 7848
telemt_desync_suppressed_total 15140
telemt_desync_frames_bucket_total{bucket="1_2"} 5527
telemt_desync_frames_bucket_total{bucket="3_10"} 8929
telemt_desync_frames_bucket_total{bucket="gt_10"} 8532
telemt_pool_swap_total 124
telemt_pool_force_close_total 3678
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 37244
telemt_me_writer_removed_unexpected_total 859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34960
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3461
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33566
telemt_me_writer_teardown_success_total{mode="normal"} 38043
telemt_me_writer_teardown_noop_total 37250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.505519
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 4831891
telemt_user_connections_current{user="hello"} 2253
telemt_user_octets_from_client{user="hello"} 143096536533 (133.27 GB)
telemt_user_octets_to_client{user="hello"} 2298406232935 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1024
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 113785.0 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6446985
telemt_connections_bad_total 551873
telemt_connections_current 1832
telemt_connections_me_current 1832
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 212031
telemt_upstream_connect_attempt_total 52924
telemt_upstream_connect_success_total 52437
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 52579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 1021
telemt_me_reader_eof_total 961
telemt_me_idle_close_by_peer_total 961
telemt_me_route_drop_no_conn_total 2241675
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4791047
telemt_me_endpoint_quarantine_total 808
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 847
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
telemt_desync_total 22909
telemt_desync_full_logged_total 7740
telemt_desync_suppressed_total 15169
telemt_desync_frames_bucket_total{bucket="1_2"} 5593
telemt_desync_frames_bucket_total{bucket="3_10"} 8784
telemt_desync_frames_bucket_total{bucket="gt_10"} 8532
telemt_pool_swap_total 122
telemt_pool_force_close_total 3553
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 38452
telemt_me_writer_removed_unexpected_total 948
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36157
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34899
telemt_me_writer_teardown_success_total{mode="normal"} 39418
telemt_me_writer_teardown_noop_total 38464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.268379
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 4785995
telemt_user_connections_current{user="hello"} 1832
telemt_user_octets_from_client{user="hello"} 135398193971 (126.10 GB)
telemt_user_octets_to_client{user="hello"} 2190328165251 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 857
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 113822.9 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20731998
telemt_connections_bad_total 1713840
telemt_connections_current 3056
telemt_connections_me_current 3056
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 626653
telemt_upstream_connect_attempt_total 203284
telemt_upstream_connect_success_total 184992
telemt_upstream_connect_fail_total 16470
telemt_upstream_connect_attempts_per_request{bucket="1"} 201462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8950
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16470
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65151
telemt_me_reconnect_success_total 2418
telemt_me_reader_eof_total 1502
telemt_me_idle_close_by_peer_total 1501
telemt_me_route_drop_no_conn_total 39574619
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16694666
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 887
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 895
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32311
telemt_desync_full_logged_total 9729
telemt_desync_suppressed_total 22582
telemt_desync_frames_bucket_total{bucket="1_2"} 7018
telemt_desync_frames_bucket_total{bucket="3_10"} 14328
telemt_desync_frames_bucket_total{bucket="gt_10"} 10965
telemt_pool_swap_total 118
telemt_pool_force_close_total 3803
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 832
telemt_me_draining_writers_reap_progress_total 35724
telemt_me_writer_removed_unexpected_total 2242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4814
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32896
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3272
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 531
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31921
telemt_me_writer_teardown_success_total{mode="normal"} 37710
telemt_me_writer_teardown_noop_total 35751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.949641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 832
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1641
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 16829407
telemt_user_connections_current{user="hello"} 3056
telemt_user_octets_from_client{user="hello"} 236416788544 (220.18 GB)
telemt_user_octets_to_client{user="hello"} 1268532757775 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1304
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 113790.2 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6219698
telemt_connections_bad_total 601928
telemt_connections_current 2242
telemt_connections_me_current 2242
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 130889
telemt_upstream_connect_attempt_total 61296
telemt_upstream_connect_success_total 60599
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 61194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 69830
telemt_me_reconnect_success_total 1837
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 2419168
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4824110
telemt_me_endpoint_quarantine_total 774
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 865
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24120
telemt_desync_full_logged_total 8454
telemt_desync_suppressed_total 15666
telemt_desync_frames_bucket_total{bucket="1_2"} 4721
telemt_desync_frames_bucket_total{bucket="3_10"} 9323
telemt_desync_frames_bucket_total{bucket="gt_10"} 10076
telemt_pool_swap_total 118
telemt_pool_force_close_total 3374
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 40255
telemt_me_writer_removed_unexpected_total 1656
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37846
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2973
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36881
telemt_me_writer_teardown_success_total{mode="normal"} 41944
telemt_me_writer_teardown_noop_total 40256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82200
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.344058
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82200
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1541
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4816538
telemt_user_connections_current{user="hello"} 2242
telemt_user_octets_from_client{user="hello"} 126560285572 (117.87 GB)
telemt_user_octets_to_client{user="hello"} 1980569157570 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50626.1 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4159906
telemt_connections_bad_total 176663
telemt_connections_current 1512
telemt_connections_me_current 1512
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1670637
telemt_upstream_connect_attempt_total 30141
telemt_upstream_connect_success_total 29944
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 30134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_reconnect_attempts_total 45968
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 691
telemt_me_idle_close_by_peer_total 691
telemt_me_route_drop_no_conn_total 1047195
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2037319
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 394
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10911
telemt_desync_full_logged_total 3780
telemt_desync_suppressed_total 7131
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 4192
telemt_desync_frames_bucket_total{bucket="gt_10"} 4712
telemt_pool_swap_total 55
telemt_pool_force_close_total 1620
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 18960
telemt_me_writer_removed_unexpected_total 764
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1656
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17340
telemt_me_writer_teardown_success_total{mode="normal"} 19751
telemt_me_writer_teardown_noop_total 18962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.511364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2040750
telemt_user_connections_current{user="hello"} 1512
telemt_user_octets_from_client{user="hello"} 55755300352 (51.93 GB)
telemt_user_octets_to_client{user="hello"} 872710683166 (812.78 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 31597.1 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223836
telemt_connections_bad_total 1822
telemt_connections_current 388
telemt_connections_me_current 388
telemt_handshake_timeouts_total 5944
telemt_upstream_connect_attempt_total 15325
telemt_upstream_connect_success_total 15289
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 343
telemt_me_reconnect_success_total 200
telemt_me_reader_eof_total 204
telemt_me_idle_close_by_peer_total 204
telemt_me_route_drop_no_conn_total 62033
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198147
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_shadow_rotate_total 274
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 40
telemt_desync_total 1133
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 832
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 34
telemt_pool_force_close_total 758
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 13821
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 867
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13158
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 756
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13063
telemt_me_writer_teardown_success_total{mode="normal"} 14025
telemt_me_writer_teardown_noop_total 13821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.093964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 181
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 197811
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 3459415748 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 120139141728 (111.89 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 113794.7 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7532810
telemt_connections_bad_total 757880
telemt_connections_current 2322
telemt_connections_me_current 2322
telemt_handshake_timeouts_total 215063
telemt_upstream_connect_attempt_total 44897
telemt_upstream_connect_success_total 44734
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 44860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_reconnect_attempts_total 1645
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 867
telemt_me_idle_close_by_peer_total 867
telemt_me_route_drop_no_conn_total 2156988
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5615211
telemt_me_endpoint_quarantine_total 815
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 876
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21997
telemt_desync_full_logged_total 7227
telemt_desync_suppressed_total 14770
telemt_desync_frames_bucket_total{bucket="1_2"} 5511
telemt_desync_frames_bucket_total{bucket="3_10"} 7978
telemt_desync_frames_bucket_total{bucket="gt_10"} 8508
telemt_pool_swap_total 126
telemt_pool_force_close_total 3361
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 40529
telemt_me_writer_removed_unexpected_total 833
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37168
telemt_me_writer_teardown_success_total{mode="normal"} 41386
telemt_me_writer_teardown_noop_total 40531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.729097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 786
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5590064
telemt_user_connections_current{user="hello"} 2322
telemt_user_octets_from_client{user="hello"} 111229203436 (103.59 GB)
telemt_user_octets_to_client{user="hello"} 2604952565248 (2.37 TB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 113791.4 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6529412
telemt_connections_bad_total 639896
telemt_connections_current 2182
telemt_connections_me_current 2182
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 176268
telemt_upstream_connect_attempt_total 60688
telemt_upstream_connect_success_total 60231
telemt_upstream_connect_fail_total 398
telemt_upstream_connect_attempts_per_request{bucket="1"} 60629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 398
telemt_me_reconnect_attempts_total 5683
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2208914
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4982840
telemt_me_endpoint_quarantine_total 897
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 872
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20628
telemt_desync_full_logged_total 6887
telemt_desync_suppressed_total 13741
telemt_desync_frames_bucket_total{bucket="1_2"} 5263
telemt_desync_frames_bucket_total{bucket="3_10"} 7546
telemt_desync_frames_bucket_total{bucket="gt_10"} 7819
telemt_pool_swap_total 124
telemt_pool_force_close_total 3311
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 39056
telemt_me_writer_removed_unexpected_total 1119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3088
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35745
telemt_me_writer_teardown_success_total{mode="normal"} 40230
telemt_me_writer_teardown_noop_total 39060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79290
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.300340
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79290
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 956
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 4985660
telemt_user_connections_current{user="hello"} 2182
telemt_user_octets_from_client{user="hello"} 94064542909 (87.60 GB)
telemt_user_octets_to_client{user="hello"} 2132690201416 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 960
telemt_user_unique_ips_recent_window{user="hello"} 270
```