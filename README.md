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

# Server Metrics 2026-03-21 16:55:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 73156.8 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2633138
telemt_connections_bad_total 156253
telemt_connections_current 1491
telemt_connections_me_current 1491
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 81717
telemt_upstream_connect_attempt_total 30713
telemt_upstream_connect_success_total 30581
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 691
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 2239412
telemt_me_route_drop_channel_closed_total 700
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2104577
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 571
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 8359
telemt_desync_full_logged_total 2901
telemt_desync_suppressed_total 5458
telemt_desync_frames_bucket_total{bucket="1_2"} 1816
telemt_desync_frames_bucket_total{bucket="3_10"} 3176
telemt_desync_frames_bucket_total{bucket="gt_10"} 3367
telemt_pool_swap_total 79
telemt_pool_force_close_total 2393
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 24772
telemt_me_writer_removed_unexpected_total 642
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23077
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22379
telemt_me_writer_teardown_success_total{mode="normal"} 25197
telemt_me_writer_teardown_noop_total 24780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49977
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 241.041967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49977
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2105732
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 29952871597 (27.90 GB)
telemt_user_octets_to_client{user="hello"} 518332896238 (482.74 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4281.8 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238084
telemt_connections_bad_total 10353
telemt_connections_current 1145
telemt_connections_me_current 1145
telemt_handshake_timeouts_total 6160
telemt_upstream_connect_attempt_total 1726
telemt_upstream_connect_success_total 1724
telemt_upstream_connect_attempts_per_request{bucket="1"} 1724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 186098
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207920
telemt_me_endpoint_quarantine_total 29
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
telemt_me_writers_active_current 44
telemt_desync_total 828
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 4
telemt_pool_force_close_total 75
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 1514
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1439
telemt_me_writer_teardown_success_total{mode="normal"} 1530
telemt_me_writer_teardown_noop_total 1514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.311136
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 204882
telemt_user_connections_current{user="hello"} 1145
telemt_user_octets_from_client{user="hello"} 1943757368 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 44544795184 (41.49 GB)
telemt_user_unique_ips_current{user="hello"} 836
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 73154.4 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5483616
telemt_connections_bad_total 456989
telemt_connections_current 3006
telemt_connections_me_current 3006
telemt_handshake_timeouts_total 180748
telemt_upstream_connect_attempt_total 26832
telemt_upstream_connect_success_total 26773
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 601
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 3425536
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4519700
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 546
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 18347
telemt_desync_full_logged_total 6186
telemt_desync_suppressed_total 12161
telemt_desync_frames_bucket_total{bucket="1_2"} 3893
telemt_desync_frames_bucket_total{bucket="3_10"} 7280
telemt_desync_frames_bucket_total{bucket="gt_10"} 7174
telemt_pool_swap_total 78
telemt_pool_force_close_total 2587
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 409
telemt_me_draining_writers_reap_progress_total 24405
telemt_me_writer_removed_unexpected_total 586
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2134
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21818
telemt_me_writer_teardown_success_total{mode="normal"} 24685
telemt_me_writer_teardown_noop_total 24439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.336594
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 409
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 4514265
telemt_user_connections_current{user="hello"} 3006
telemt_user_octets_from_client{user="hello"} 71278113748 (66.38 GB)
telemt_user_octets_to_client{user="hello"} 1423533332064 (1.29 TB)
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 73156.1 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4377993
telemt_connections_bad_total 447256
telemt_connections_current 3912
telemt_connections_me_current 3912
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 149057
telemt_upstream_connect_attempt_total 31175
telemt_upstream_connect_success_total 30886
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 31028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1423
telemt_me_reconnect_success_total 625
telemt_me_reader_eof_total 590
telemt_me_idle_close_by_peer_total 590
telemt_me_route_drop_no_conn_total 1448259
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3249787
telemt_me_endpoint_quarantine_total 461
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 558
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
telemt_desync_total 15539
telemt_desync_full_logged_total 5126
telemt_desync_suppressed_total 10413
telemt_desync_frames_bucket_total{bucket="1_2"} 3829
telemt_desync_frames_bucket_total{bucket="3_10"} 6031
telemt_desync_frames_bucket_total{bucket="gt_10"} 5679
telemt_pool_swap_total 80
telemt_pool_force_close_total 2375
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 23508
telemt_me_writer_removed_unexpected_total 571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2029
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22010
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21133
telemt_me_writer_teardown_success_total{mode="normal"} 24039
telemt_me_writer_teardown_noop_total 23511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.930490
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3248738
telemt_user_connections_current{user="hello"} 3912
telemt_user_octets_from_client{user="hello"} 75661764337 (70.47 GB)
telemt_user_octets_to_client{user="hello"} 1484893607283 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1448
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 73119.6 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4320108
telemt_connections_bad_total 429080
telemt_connections_current 3729
telemt_connections_me_current 3729
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 129116
telemt_upstream_connect_attempt_total 36413
telemt_upstream_connect_success_total 36169
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 870
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1507
telemt_me_reconnect_success_total 679
telemt_me_reader_eof_total 625
telemt_me_idle_close_by_peer_total 625
telemt_me_route_drop_no_conn_total 1537957
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3229617
telemt_me_endpoint_quarantine_total 509
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 549
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 15032
telemt_desync_full_logged_total 4926
telemt_desync_suppressed_total 10106
telemt_desync_frames_bucket_total{bucket="1_2"} 3718
telemt_desync_frames_bucket_total{bucket="3_10"} 5674
telemt_desync_frames_bucket_total{bucket="gt_10"} 5640
telemt_pool_swap_total 78
telemt_pool_force_close_total 2274
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 273
telemt_me_draining_writers_reap_progress_total 24877
telemt_me_writer_removed_unexpected_total 593
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2113
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23381
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2082
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22603
telemt_me_writer_teardown_success_total{mode="normal"} 25494
telemt_me_writer_teardown_noop_total 24884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50378
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.920459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50378
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 273
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 586
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 3232703
telemt_user_connections_current{user="hello"} 3729
telemt_user_octets_from_client{user="hello"} 79834189865 (74.35 GB)
telemt_user_octets_to_client{user="hello"} 1483935216216 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1379
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 73158.9 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14998494
telemt_connections_bad_total 964454
telemt_connections_current 5405
telemt_connections_me_current 5405
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 435623
telemt_upstream_connect_attempt_total 147549
telemt_upstream_connect_success_total 131775
telemt_upstream_connect_fail_total 14626
telemt_upstream_connect_attempts_per_request{bucket="1"} 146401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14626
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4123
telemt_me_reconnect_success_total 1527
telemt_me_reader_eof_total 1056
telemt_me_idle_close_by_peer_total 1055
telemt_me_route_drop_no_conn_total 29742707
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12358988
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 195
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 195
telemt_me_single_endpoint_shadow_rotate_total 572
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 21765
telemt_desync_full_logged_total 6688
telemt_desync_suppressed_total 15077
telemt_desync_frames_bucket_total{bucket="1_2"} 4762
telemt_desync_frames_bucket_total{bucket="3_10"} 9499
telemt_desync_frames_bucket_total{bucket="gt_10"} 7504
telemt_pool_swap_total 74
telemt_pool_force_close_total 2439
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 556
telemt_me_draining_writers_reap_progress_total 23109
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3091
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20670
telemt_me_writer_teardown_success_total{mode="normal"} 24330
telemt_me_writer_teardown_noop_total 23121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.381057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 556
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1067
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 12457489
telemt_user_connections_current{user="hello"} 5405
telemt_user_octets_from_client{user="hello"} 101039809806 (94.10 GB)
telemt_user_octets_to_client{user="hello"} 843427518895 (785.50 GB)
telemt_user_msgs_from_client{user="hello"} 290173
telemt_user_msgs_to_client{user="hello"} 585212
telemt_user_unique_ips_current{user="hello"} 1984
telemt_user_unique_ips_recent_window{user="hello"} 963
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 73126.3 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4316629
telemt_connections_bad_total 455873
telemt_connections_current 3196
telemt_connections_me_current 3196
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 91697
telemt_upstream_connect_attempt_total 30394
telemt_upstream_connect_success_total 30019
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 30342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 3117
telemt_me_reconnect_success_total 1095
telemt_me_reader_eof_total 1079
telemt_me_idle_close_by_peer_total 1079
telemt_me_route_drop_no_conn_total 1846502
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3339454
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 543
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
telemt_desync_total 16252
telemt_desync_full_logged_total 5642
telemt_desync_suppressed_total 10610
telemt_desync_frames_bucket_total{bucket="1_2"} 3162
telemt_desync_frames_bucket_total{bucket="3_10"} 6432
telemt_desync_frames_bucket_total{bucket="gt_10"} 6658
telemt_pool_swap_total 73
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 226
telemt_me_draining_writers_reap_progress_total 25534
telemt_me_writer_removed_unexpected_total 1046
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24051
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 312
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23360
telemt_me_writer_teardown_success_total{mode="normal"} 26616
telemt_me_writer_teardown_noop_total 25535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52151
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.872818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52151
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 226
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 3322192
telemt_user_connections_current{user="hello"} 3196
telemt_user_octets_from_client{user="hello"} 86786966308 (80.83 GB)
telemt_user_octets_to_client{user="hello"} 1360765477722 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 759
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 9962.1 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1509299
telemt_connections_bad_total 54423
telemt_connections_current 4209
telemt_connections_me_current 4209
telemt_handshake_timeouts_total 689994
telemt_upstream_connect_attempt_total 3324
telemt_upstream_connect_success_total 3264
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 3317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 421
telemt_me_reconnect_success_total 113
telemt_me_reader_eof_total 106
telemt_me_idle_close_by_peer_total 106
telemt_me_route_drop_no_conn_total 531869
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699183
telemt_me_endpoint_quarantine_total 39
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 75
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
telemt_me_writers_warm_current 16
telemt_desync_total 3780
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 2578
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 1411
telemt_desync_frames_bucket_total{bucket="gt_10"} 1661
telemt_pool_swap_total 9
telemt_pool_force_close_total 296
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 2816
telemt_me_writer_removed_unexpected_total 107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2672
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2520
telemt_me_writer_teardown_success_total{mode="normal"} 2923
telemt_me_writer_teardown_noop_total 2816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.845546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 698174
telemt_user_connections_current{user="hello"} 4209
telemt_user_octets_from_client{user="hello"} 16478606724 (15.35 GB)
telemt_user_octets_to_client{user="hello"} 266027689140 (247.76 GB)
telemt_user_unique_ips_current{user="hello"} 1741
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 71112.5 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1378453
telemt_connections_bad_total 151392
telemt_connections_current 2203
telemt_connections_me_current 2203
telemt_handshake_timeouts_total 486082
telemt_upstream_connect_attempt_total 32708
telemt_upstream_connect_success_total 32698
telemt_upstream_connect_attempts_per_request{bucket="1"} 32698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 306667
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658459
telemt_me_endpoint_quarantine_total 620
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 589
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3890
telemt_desync_full_logged_total 1394
telemt_desync_suppressed_total 2496
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1755
telemt_pool_swap_total 77
telemt_pool_force_close_total 1828
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 29299
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2225
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27641
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1798
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27471
telemt_me_writer_teardown_success_total{mode="normal"} 29866
telemt_me_writer_teardown_noop_total 29299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.839701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 658000
telemt_user_connections_current{user="hello"} 2203
telemt_user_octets_from_client{user="hello"} 13528501343 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 253282942673 (235.89 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 378
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 73130.9 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4841764
telemt_connections_bad_total 445762
telemt_connections_current 4556
telemt_connections_me_current 4556
telemt_handshake_timeouts_total 158234
telemt_upstream_connect_attempt_total 28714
telemt_upstream_connect_success_total 28595
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 28678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 1229
telemt_me_reconnect_success_total 640
telemt_me_reader_eof_total 610
telemt_me_idle_close_by_peer_total 610
telemt_me_route_drop_no_conn_total 1477543
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3824495
telemt_me_endpoint_quarantine_total 519
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 562
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 14880
telemt_desync_full_logged_total 4928
telemt_desync_suppressed_total 9952
telemt_desync_frames_bucket_total{bucket="1_2"} 3524
telemt_desync_frames_bucket_total{bucket="3_10"} 5518
telemt_desync_frames_bucket_total{bucket="gt_10"} 5838
telemt_pool_swap_total 81
telemt_pool_force_close_total 2152
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 25764
telemt_me_writer_removed_unexpected_total 596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2080
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24284
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23612
telemt_me_writer_teardown_success_total{mode="normal"} 26364
telemt_me_writer_teardown_noop_total 25765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.401707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 569
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3814726
telemt_user_connections_current{user="hello"} 4556
telemt_user_octets_from_client{user="hello"} 75608725348 (70.42 GB)
telemt_user_octets_to_client{user="hello"} 1782130460880 (1.62 TB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 944
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 73127.5 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4259192
telemt_connections_bad_total 384616
telemt_connections_current 3995
telemt_connections_me_current 3995
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 130709
telemt_upstream_connect_attempt_total 45174
telemt_upstream_connect_success_total 44851
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 45118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 605
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_reconnect_attempts_total 4129
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 793
telemt_me_idle_close_by_peer_total 793
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1558819
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3392412
telemt_me_endpoint_quarantine_total 608
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 556
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
telemt_desync_total 13285
telemt_desync_full_logged_total 4518
telemt_desync_suppressed_total 8767
telemt_desync_frames_bucket_total{bucket="1_2"} 3301
telemt_desync_frames_bucket_total{bucket="3_10"} 4937
telemt_desync_frames_bucket_total{bucket="gt_10"} 5047
telemt_pool_swap_total 79
telemt_pool_force_close_total 2095
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 25089
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23441
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22994
telemt_me_writer_teardown_success_total{mode="normal"} 25928
telemt_me_writer_teardown_noop_total 25091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.200170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 183
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 3400108
telemt_user_connections_current{user="hello"} 3995
telemt_user_octets_from_client{user="hello"} 61733449265 (57.49 GB)
telemt_user_octets_to_client{user="hello"} 1435696205264 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1407
telemt_user_unique_ips_recent_window{user="hello"} 998
```