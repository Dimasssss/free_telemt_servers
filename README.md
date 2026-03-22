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

# Server Metrics 2026-03-22 20:56:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85790.3 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3163309
telemt_connections_bad_total 223736
telemt_connections_current 904
telemt_connections_me_current 904
telemt_handshake_timeouts_total 100989
telemt_upstream_connect_attempt_total 31458
telemt_upstream_connect_success_total 31457
telemt_upstream_connect_attempts_per_request{bucket="1"} 31457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1277
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 535
telemt_me_idle_close_by_peer_total 535
telemt_me_route_drop_no_conn_total 2816589
telemt_me_route_drop_channel_closed_total 1135
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2670139
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 665
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
telemt_desync_total 11537
telemt_desync_full_logged_total 3614
telemt_desync_suppressed_total 7923
telemt_desync_frames_bucket_total{bucket="1_2"} 3116
telemt_desync_frames_bucket_total{bucket="3_10"} 4224
telemt_desync_frames_bucket_total{bucket="gt_10"} 4197
telemt_pool_swap_total 95
telemt_pool_force_close_total 2968
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 28770
telemt_me_writer_removed_unexpected_total 519
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2097
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26897
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25802
telemt_me_writer_teardown_success_total{mode="normal"} 28994
telemt_me_writer_teardown_noop_total 28781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57775
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 332.170936
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57775
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 466
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2660949
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 38926494112 (36.25 GB)
telemt_user_octets_to_client{user="hello"} 711905805268 (663.01 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 99156.5 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3880483
telemt_connections_bad_total 343042
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98697
telemt_upstream_connect_attempt_total 59683
telemt_upstream_connect_success_total 58955
telemt_upstream_connect_fail_total 643
telemt_upstream_connect_attempts_per_request{bucket="1"} 59598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 643
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6867
telemt_me_reconnect_success_total 2678
telemt_me_reader_eof_total 2627
telemt_me_idle_close_by_peer_total 2627
telemt_me_route_drop_no_conn_total 3619390
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3093292
telemt_me_endpoint_quarantine_total 756
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 764
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
telemt_me_writers_active_current 44
telemt_desync_total 12484
telemt_desync_full_logged_total 6993
telemt_desync_suppressed_total 5491
telemt_desync_frames_bucket_total{bucket="1_2"} 2834
telemt_desync_frames_bucket_total{bucket="3_10"} 4899
telemt_desync_frames_bucket_total{bucket="gt_10"} 4751
telemt_pool_swap_total 93
telemt_pool_force_close_total 2802
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 39498
telemt_me_writer_removed_unexpected_total 2570
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36696
telemt_me_writer_teardown_success_total{mode="normal"} 42088
telemt_me_writer_teardown_noop_total 39499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81587
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.353123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81587
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 2360
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 3104002
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 40744455387 (37.95 GB)
telemt_user_octets_to_client{user="hello"} 754032324610 (702.25 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 174016.4 (48h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16044635
telemt_connections_bad_total 1554736
telemt_connections_current 1224
telemt_connections_me_current 1224
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394073
telemt_upstream_connect_attempt_total 77188
telemt_upstream_connect_success_total 77088
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1691
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2830
telemt_me_reconnect_success_total 1466
telemt_me_reader_eof_total 1411
telemt_me_idle_close_by_peer_total 1409
telemt_me_route_drop_no_conn_total 14002034
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12788354
telemt_me_endpoint_quarantine_total 1109
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1299
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
telemt_me_writers_active_current 44
telemt_desync_total 52772
telemt_desync_full_logged_total 16647
telemt_desync_suppressed_total 36125
telemt_desync_frames_bucket_total{bucket="1_2"} 11745
telemt_desync_frames_bucket_total{bucket="3_10"} 20555
telemt_desync_frames_bucket_total{bucket="gt_10"} 20472
telemt_pool_swap_total 188
telemt_pool_force_close_total 6331
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1022
telemt_me_draining_writers_reap_progress_total 57247
telemt_me_writer_removed_unexpected_total 1361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50916
telemt_me_writer_teardown_success_total{mode="normal"} 57887
telemt_me_writer_teardown_noop_total 57298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.789421
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1022
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1265
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12788714
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 187493192221 (174.62 GB)
telemt_user_octets_to_client{user="hello"} 3417255194819 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 174017.8 (48h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11626220
telemt_connections_bad_total 1170453
telemt_connections_current 1101
telemt_connections_me_current 1101
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343365
telemt_upstream_connect_attempt_total 91678
telemt_upstream_connect_success_total 90390
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3779
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4266
telemt_me_reconnect_success_total 1776
telemt_me_reader_eof_total 1634
telemt_me_idle_close_by_peer_total 1634
telemt_me_route_drop_no_conn_total 4521834
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8661704
telemt_me_endpoint_quarantine_total 1104
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1319
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 49
telemt_desync_total 38340
telemt_desync_full_logged_total 12898
telemt_desync_suppressed_total 25442
telemt_desync_frames_bucket_total{bucket="1_2"} 9460
telemt_desync_frames_bucket_total{bucket="3_10"} 14748
telemt_desync_frames_bucket_total{bucket="gt_10"} 14132
telemt_pool_swap_total 185
telemt_pool_force_close_total 5700
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 55628
telemt_me_writer_removed_unexpected_total 1672
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51982
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49928
telemt_me_writer_teardown_success_total{mode="normal"} 57148
telemt_me_writer_teardown_noop_total 55653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112801
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.784047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112801
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1509
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8599658
telemt_user_connections_current{user="hello"} 1101
telemt_user_octets_from_client{user="hello"} 216148422788 (201.30 GB)
telemt_user_octets_to_client{user="hello"} 3890871615559 (3.54 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 173982.3 (48h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10888000
telemt_connections_bad_total 944137
telemt_connections_current 842
telemt_connections_me_current 842
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344450
telemt_upstream_connect_attempt_total 75336
telemt_upstream_connect_success_total 74038
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 74230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2268
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1411
telemt_me_reconnect_attempts_total 5281
telemt_me_reconnect_success_total 2163
telemt_me_reader_eof_total 1900
telemt_me_idle_close_by_peer_total 1899
telemt_me_route_drop_no_conn_total 5298094
telemt_me_route_drop_channel_closed_total 379
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8238070
telemt_me_endpoint_quarantine_total 1193
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1274
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
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
telemt_desync_total 37779
telemt_desync_full_logged_total 12514
telemt_desync_suppressed_total 25265
telemt_desync_frames_bucket_total{bucket="1_2"} 9544
telemt_desync_frames_bucket_total{bucket="3_10"} 14449
telemt_desync_frames_bucket_total{bucket="gt_10"} 13786
telemt_pool_swap_total 182
telemt_pool_force_close_total 5647
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 720
telemt_me_draining_writers_reap_progress_total 55900
telemt_me_writer_removed_unexpected_total 2048
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5745
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5082
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50253
telemt_me_writer_teardown_success_total{mode="normal"} 57872
telemt_me_writer_teardown_noop_total 55971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.061516
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 720
telemt_me_refill_failed_total 165
telemt_me_writer_restored_same_endpoint_total 1867
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 8230147
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 191612752041 (178.45 GB)
telemt_user_octets_to_client{user="hello"} 3423787068225 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44261.9 (12h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10932079
telemt_connections_bad_total 661985
telemt_connections_current 1448
telemt_connections_me_current 1448
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 240804
telemt_upstream_connect_attempt_total 49478
telemt_upstream_connect_success_total 46975
telemt_upstream_connect_fail_total 1729
telemt_upstream_connect_attempts_per_request{bucket="1"} 48704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1729
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6960
telemt_me_reconnect_success_total 1007
telemt_me_reader_eof_total 615
telemt_me_idle_close_by_peer_total 614
telemt_me_route_drop_no_conn_total 25230201
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9078923
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 41
telemt_desync_total 15032
telemt_desync_full_logged_total 3987
telemt_desync_suppressed_total 11045
telemt_desync_frames_bucket_total{bucket="1_2"} 2824
telemt_desync_frames_bucket_total{bucket="3_10"} 6095
telemt_desync_frames_bucket_total{bucket="gt_10"} 6113
telemt_pool_swap_total 45
telemt_pool_force_close_total 1591
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 445
telemt_me_draining_writers_reap_progress_total 12772
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1928
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11694
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1285
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11181
telemt_me_writer_teardown_success_total{mode="normal"} 13622
telemt_me_writer_teardown_noop_total 12791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26413
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.971332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26413
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 445
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 653
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9103689
telemt_user_connections_current{user="hello"} 1448
telemt_user_octets_from_client{user="hello"} 84496137364 (78.69 GB)
telemt_user_octets_to_client{user="hello"} 526047816602 (489.92 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 173988.6 (48h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10781728
telemt_connections_bad_total 909608
telemt_connections_current 1062
telemt_connections_me_current 1062
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237441
telemt_upstream_connect_attempt_total 104306
telemt_upstream_connect_success_total 103211
telemt_upstream_connect_fail_total 934
telemt_upstream_connect_attempts_per_request{bucket="1"} 104145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 934
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72448
telemt_me_reconnect_success_total 2852
telemt_me_reader_eof_total 2546
telemt_me_idle_close_by_peer_total 2544
telemt_me_route_drop_no_conn_total 5219771
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8519601
telemt_me_endpoint_quarantine_total 1150
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 44
telemt_desync_total 45427
telemt_desync_full_logged_total 15502
telemt_desync_suppressed_total 29925
telemt_desync_frames_bucket_total{bucket="1_2"} 9216
telemt_desync_frames_bucket_total{bucket="3_10"} 17401
telemt_desync_frames_bucket_total{bucket="gt_10"} 18810
telemt_pool_swap_total 178
telemt_pool_force_close_total 5319
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 59705
telemt_me_writer_removed_unexpected_total 2582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56001
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4589
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54386
telemt_me_writer_teardown_success_total{mode="normal"} 62315
telemt_me_writer_teardown_noop_total 59706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.109170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2401
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8522787
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 192941761089 (179.69 GB)
telemt_user_octets_to_client{user="hello"} 3247089347340 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 110824.7 (30h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11393931
telemt_connections_bad_total 456005
telemt_connections_current 1261
telemt_connections_me_current 1261
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4674443
telemt_upstream_connect_attempt_total 52421
telemt_upstream_connect_success_total 52028
telemt_upstream_connect_fail_total 383
telemt_upstream_connect_attempts_per_request{bucket="1"} 52411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 383
telemt_me_reconnect_attempts_total 48634
telemt_me_reconnect_success_total 1690
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1350
telemt_me_route_drop_no_conn_total 4053723
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5492618
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 835
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30877
telemt_desync_full_logged_total 10490
telemt_desync_suppressed_total 20387
telemt_desync_frames_bucket_total{bucket="1_2"} 6136
telemt_desync_frames_bucket_total{bucket="3_10"} 12219
telemt_desync_frames_bucket_total{bucket="gt_10"} 12522
telemt_pool_swap_total 117
telemt_pool_force_close_total 3534
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 38661
telemt_me_writer_removed_unexpected_total 1410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3390
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36716
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3093
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35127
telemt_me_writer_teardown_success_total{mode="normal"} 40106
telemt_me_writer_teardown_noop_total 38668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.532695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 2728
telemt_me_writer_restored_same_endpoint_total 1502
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5485378
telemt_user_connections_current{user="hello"} 1261
telemt_user_octets_from_client{user="hello"} 117735975980 (109.65 GB)
telemt_user_octets_to_client{user="hello"} 2104107130686 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 91795.4 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1391453
telemt_connections_bad_total 34388
telemt_connections_current 777
telemt_connections_me_current 777
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25831
telemt_upstream_connect_attempt_total 43158
telemt_upstream_connect_success_total 43026
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 43131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 740
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2040
telemt_me_reconnect_success_total 827
telemt_me_reader_eof_total 809
telemt_me_idle_close_by_peer_total 809
telemt_me_route_drop_no_conn_total 485486
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1234245
telemt_me_endpoint_quarantine_total 753
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 754
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
telemt_me_writers_active_current 45
telemt_desync_total 7544
telemt_desync_full_logged_total 2328
telemt_desync_suppressed_total 5216
telemt_desync_frames_bucket_total{bucket="1_2"} 1708
telemt_desync_frames_bucket_total{bucket="3_10"} 2922
telemt_desync_frames_bucket_total{bucket="gt_10"} 2914
telemt_pool_swap_total 98
telemt_pool_force_close_total 2549
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36004
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33455
telemt_me_writer_teardown_success_total{mode="normal"} 36816
telemt_me_writer_teardown_noop_total 36008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.557917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 701
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1230265
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 23916821549 (22.27 GB)
telemt_user_octets_to_client{user="hello"} 520902449663 (485.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 173993.1 (48h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13110760
telemt_connections_bad_total 1543368
telemt_connections_current 1294
telemt_connections_me_current 1294
telemt_handshake_timeouts_total 376094
telemt_upstream_connect_attempt_total 66004
telemt_upstream_connect_success_total 65671
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 65869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2579
telemt_me_reconnect_success_total 1356
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 4451406
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9915871
telemt_me_endpoint_quarantine_total 1177
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1303
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41284
telemt_desync_full_logged_total 13443
telemt_desync_suppressed_total 27841
telemt_desync_frames_bucket_total{bucket="1_2"} 9929
telemt_desync_frames_bucket_total{bucket="3_10"} 15208
telemt_desync_frames_bucket_total{bucket="gt_10"} 16147
telemt_pool_swap_total 193
telemt_pool_force_close_total 5293
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 59495
telemt_me_writer_removed_unexpected_total 1273
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54202
telemt_me_writer_teardown_success_total{mode="normal"} 60808
telemt_me_writer_teardown_noop_total 59497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.529180
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1187
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9882778
telemt_user_connections_current{user="hello"} 1294
telemt_user_octets_from_client{user="hello"} 193140847720 (179.88 GB)
telemt_user_octets_to_client{user="hello"} 4370969241676 (3.98 TB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 173989.7 (48h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11399231
telemt_connections_bad_total 1289793
telemt_connections_current 988
telemt_connections_me_current 988
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 299988
telemt_upstream_connect_attempt_total 92440
telemt_upstream_connect_success_total 91608
telemt_upstream_connect_fail_total 625
telemt_upstream_connect_attempts_per_request{bucket="1"} 92233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 625
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9923
telemt_me_reconnect_success_total 2387
telemt_me_reader_eof_total 2232
telemt_me_idle_close_by_peer_total 2231
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5612379
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8817951
telemt_me_endpoint_quarantine_total 1333
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 40412
telemt_desync_full_logged_total 13050
telemt_desync_suppressed_total 27362
telemt_desync_frames_bucket_total{bucket="1_2"} 10119
telemt_desync_frames_bucket_total{bucket="3_10"} 14990
telemt_desync_frames_bucket_total{bucket="gt_10"} 15303
telemt_pool_swap_total 183
telemt_pool_force_close_total 5089
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 59249
telemt_me_writer_removed_unexpected_total 2263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6187
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55402
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54160
telemt_me_writer_teardown_success_total{mode="normal"} 61589
telemt_me_writer_teardown_noop_total 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.241097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 1944
telemt_me_writer_restored_fallback_total 110
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 8823445
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 156068433121 (145.35 GB)
telemt_user_octets_to_client{user="hello"} 3422366588895 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 117
```