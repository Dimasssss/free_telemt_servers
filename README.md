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

# Server Metrics 2026-03-22 08:13:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40010.6 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924943
telemt_connections_bad_total 54978
telemt_connections_current 1612
telemt_connections_me_current 1612
telemt_handshake_timeouts_total 42865
telemt_upstream_connect_attempt_total 16029
telemt_upstream_connect_success_total 16028
telemt_upstream_connect_attempts_per_request{bucket="1"} 16028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 477
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 533413
telemt_me_route_drop_channel_closed_total 153
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769808
telemt_me_endpoint_quarantine_total 287
telemt_me_single_endpoint_shadow_rotate_total 324
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5805
telemt_desync_full_logged_total 1632
telemt_desync_suppressed_total 4173
telemt_desync_frames_bucket_total{bucket="1_2"} 1805
telemt_desync_frames_bucket_total{bucket="3_10"} 2190
telemt_desync_frames_bucket_total{bucket="gt_10"} 1810
telemt_pool_swap_total 44
telemt_pool_force_close_total 1236
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 14543
telemt_me_writer_removed_unexpected_total 246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13735
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13307
telemt_me_writer_teardown_success_total{mode="normal"} 14741
telemt_me_writer_teardown_noop_total 14545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.400583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29286
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 768386
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 10411594920 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 247555378836 (230.55 GB)
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 53377.0 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1398726
telemt_connections_bad_total 137746
telemt_connections_current 2400
telemt_connections_me_current 2400
telemt_handshake_timeouts_total 41391
telemt_upstream_connect_attempt_total 27966
telemt_upstream_connect_success_total 27547
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 27914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2097
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 817
telemt_me_idle_close_by_peer_total 817
telemt_me_route_drop_no_conn_total 582501
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055941
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 425
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
telemt_me_writers_active_current 128
telemt_desync_total 4651
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 1947
telemt_desync_frames_bucket_total{bucket="1_2"} 1009
telemt_desync_frames_bucket_total{bucket="3_10"} 1804
telemt_desync_frames_bucket_total{bucket="gt_10"} 1838
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 21818
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20574
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20338
telemt_me_writer_teardown_success_total{mode="normal"} 22594
telemt_me_writer_teardown_noop_total 21818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.937382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 726
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1057593
telemt_user_connections_current{user="hello"} 2400
telemt_user_octets_from_client{user="hello"} 16424332634 (15.30 GB)
telemt_user_octets_to_client{user="hello"} 373777715719 (348.11 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 128236.9 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9486520
telemt_connections_bad_total 854280
telemt_connections_current 5098
telemt_connections_me_current 5098
telemt_handshake_timeouts_total 288422
telemt_upstream_connect_attempt_total 47263
telemt_upstream_connect_success_total 47183
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1885
telemt_me_reconnect_success_total 975
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 5236576
telemt_me_route_drop_channel_closed_total 79
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7444888
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 961
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
telemt_me_writers_active_current 85
telemt_desync_total 32365
telemt_desync_full_logged_total 10662
telemt_desync_suppressed_total 21703
telemt_desync_frames_bucket_total{bucket="1_2"} 7081
telemt_desync_frames_bucket_total{bucket="3_10"} 12545
telemt_desync_frames_bucket_total{bucket="gt_10"} 12739
telemt_pool_swap_total 138
telemt_pool_force_close_total 4564
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 43086
telemt_me_writer_removed_unexpected_total 945
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4287
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38522
telemt_me_writer_teardown_success_total{mode="normal"} 43509
telemt_me_writer_teardown_noop_total 43130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86639
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 182.310658
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86639
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 873
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 7435294
telemt_user_connections_current{user="hello"} 5098
telemt_user_octets_from_client{user="hello"} 123848627436 (115.34 GB)
telemt_user_octets_to_client{user="hello"} 2505311196840 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 1962
telemt_user_unique_ips_recent_window{user="hello"} 716
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 128238.1 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7771882
telemt_connections_bad_total 689238
telemt_connections_current 4050
telemt_connections_me_current 4050
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 252066
telemt_upstream_connect_attempt_total 53428
telemt_upstream_connect_success_total 52954
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 53196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2812
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 982
telemt_me_idle_close_by_peer_total 982
telemt_me_route_drop_no_conn_total 2606695
telemt_me_route_drop_channel_closed_total 314
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5752112
telemt_me_endpoint_quarantine_total 813
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 989
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
telemt_me_writers_active_current 45
telemt_desync_total 26374
telemt_desync_full_logged_total 9021
telemt_desync_suppressed_total 17353
telemt_desync_frames_bucket_total{bucket="1_2"} 6332
telemt_desync_frames_bucket_total{bucket="3_10"} 10211
telemt_desync_frames_bucket_total{bucket="gt_10"} 9831
telemt_pool_swap_total 140
telemt_pool_force_close_total 4180
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 446
telemt_me_draining_writers_reap_progress_total 41500
telemt_me_writer_removed_unexpected_total 1004
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38887
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37320
telemt_me_writer_teardown_success_total{mode="normal"} 42416
telemt_me_writer_teardown_noop_total 41506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83922
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.933319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83922
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 446
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5674883
telemt_user_connections_current{user="hello"} 4050
telemt_user_octets_from_client{user="hello"} 158127795555 (147.27 GB)
telemt_user_octets_to_client{user="hello"} 2725767410266 (2.48 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1540
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 128202.3 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7493717
telemt_connections_bad_total 620237
telemt_connections_current 3674
telemt_connections_me_current 3674
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 247594
telemt_upstream_connect_attempt_total 57844
telemt_upstream_connect_success_total 57174
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2783
telemt_me_reconnect_success_total 1213
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1110
telemt_me_route_drop_no_conn_total 3016351
telemt_me_route_drop_channel_closed_total 179
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5587838
telemt_me_endpoint_quarantine_total 906
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 949
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
telemt_desync_total 26170
telemt_desync_full_logged_total 8917
telemt_desync_suppressed_total 17253
telemt_desync_frames_bucket_total{bucket="1_2"} 6317
telemt_desync_frames_bucket_total{bucket="3_10"} 10049
telemt_desync_frames_bucket_total{bucket="gt_10"} 9804
telemt_pool_swap_total 137
telemt_pool_force_close_total 4078
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 473
telemt_me_draining_writers_reap_progress_total 42529
telemt_me_writer_removed_unexpected_total 1121
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39852
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3771
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38451
telemt_me_writer_teardown_success_total{mode="normal"} 43633
telemt_me_writer_teardown_noop_total 42541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.390756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 473
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1050
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 5580971
telemt_user_connections_current{user="hello"} 3674
telemt_user_octets_from_client{user="hello"} 146070792155 (136.04 GB)
telemt_user_octets_to_client{user="hello"} 2484492342279 (2.26 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1504
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 128241.5 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24080958
telemt_connections_bad_total 1974818
telemt_connections_current 5702
telemt_connections_me_current 5702
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 695929
telemt_upstream_connect_attempt_total 241429
telemt_upstream_connect_success_total 221673
telemt_upstream_connect_fail_total 17759
telemt_upstream_connect_attempts_per_request{bucket="1"} 239432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17759
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 66519
telemt_me_reconnect_success_total 2697
telemt_me_reader_eof_total 1677
telemt_me_idle_close_by_peer_total 1675
telemt_me_route_drop_no_conn_total 46663433
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19469007
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 1007
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_desync_total 37749
telemt_desync_full_logged_total 11157
telemt_desync_suppressed_total 26592
telemt_desync_frames_bucket_total{bucket="1_2"} 8374
telemt_desync_frames_bucket_total{bucket="3_10"} 16697
telemt_desync_frames_bucket_total{bucket="gt_10"} 12678
telemt_pool_swap_total 133
telemt_pool_force_close_total 4217
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 973
telemt_me_draining_writers_reap_progress_total 39940
telemt_me_writer_removed_unexpected_total 2500
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36762
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 595
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35723
telemt_me_writer_teardown_success_total{mode="normal"} 42164
telemt_me_writer_teardown_noop_total 39972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.430914
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 973
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1825
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 19634437
telemt_user_connections_current{user="hello"} 5702
telemt_user_octets_from_client{user="hello"} 277614720927 (258.55 GB)
telemt_user_octets_to_client{user="hello"} 1436656557703 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2116
telemt_user_unique_ips_recent_window{user="hello"} 1222
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 128209.0 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7124227
telemt_connections_bad_total 644987
telemt_connections_current 4388
telemt_connections_me_current 4388
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 146461
telemt_upstream_connect_attempt_total 66301
telemt_upstream_connect_success_total 65514
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 66183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_reconnect_attempts_total 70257
telemt_me_reconnect_success_total 1985
telemt_me_reader_eof_total 1745
telemt_me_idle_close_by_peer_total 1744
telemt_me_route_drop_no_conn_total 2756688
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5593951
telemt_me_endpoint_quarantine_total 866
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 974
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
telemt_desync_total 28147
telemt_desync_full_logged_total 9810
telemt_desync_suppressed_total 18337
telemt_desync_frames_bucket_total{bucket="1_2"} 5623
telemt_desync_frames_bucket_total{bucket="3_10"} 10830
telemt_desync_frames_bucket_total{bucket="gt_10"} 11694
telemt_pool_swap_total 134
telemt_pool_force_close_total 3863
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 44696
telemt_me_writer_removed_unexpected_total 1776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4492
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42005
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 428
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40833
telemt_me_writer_teardown_success_total{mode="normal"} 46497
telemt_me_writer_teardown_noop_total 44697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.239738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 4226
telemt_me_writer_restored_same_endpoint_total 1647
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 5584635
telemt_user_connections_current{user="hello"} 4388
telemt_user_octets_from_client{user="hello"} 141033546232 (131.35 GB)
telemt_user_octets_to_client{user="hello"} 2325416774502 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1662
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 65044.9 (18h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5499114
telemt_connections_bad_total 216959
telemt_connections_current 3870
telemt_connections_me_current 3870
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2183910
telemt_upstream_connect_attempt_total 35412
telemt_upstream_connect_success_total 35162
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 35405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_reconnect_attempts_total 46411
telemt_me_reconnect_success_total 1153
telemt_me_reader_eof_total 836
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 1367552
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2752963
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 500
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14816
telemt_desync_full_logged_total 5074
telemt_desync_suppressed_total 9742
telemt_desync_frames_bucket_total{bucket="1_2"} 2886
telemt_desync_frames_bucket_total{bucket="3_10"} 5701
telemt_desync_frames_bucket_total{bucket="gt_10"} 6229
telemt_pool_swap_total 70
telemt_pool_force_close_total 2085
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 197
telemt_me_draining_writers_reap_progress_total 23623
telemt_me_writer_removed_unexpected_total 906
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22515
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21538
telemt_me_writer_teardown_success_total{mode="normal"} 24551
telemt_me_writer_teardown_noop_total 23629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48180
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.435285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48180
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 197
telemt_me_refill_failed_total 2629
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4274
telemt_user_connections_total{user="hello"} 2754216
telemt_user_connections_current{user="hello"} 3870
telemt_user_octets_from_client{user="hello"} 70458828908 (65.62 GB)
telemt_user_octets_to_client{user="hello"} 1214272759990 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1444
telemt_user_unique_ips_recent_window{user="hello"} 578
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46015.7 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385255
telemt_connections_bad_total 2744
telemt_connections_current 1073
telemt_connections_me_current 1073
telemt_handshake_timeouts_total 8033
telemt_upstream_connect_attempt_total 21762
telemt_upstream_connect_success_total 21707
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 21758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 934
telemt_me_reconnect_success_total 320
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 120657
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350485
telemt_me_endpoint_quarantine_total 433
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 394
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
telemt_me_writers_warm_current 38
telemt_desync_total 1600
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1136
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 50
telemt_pool_force_close_total 1141
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 19621
telemt_me_writer_removed_unexpected_total 305
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18637
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18480
telemt_me_writer_teardown_success_total{mode="normal"} 19940
telemt_me_writer_teardown_noop_total 19621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.811587
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 349902
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 6642089320 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 186833360456 (174.00 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 128213.4 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8748161
telemt_connections_bad_total 980272
telemt_connections_current 4570
telemt_connections_me_current 4570
telemt_handshake_timeouts_total 244439
telemt_upstream_connect_attempt_total 50023
telemt_upstream_connect_success_total 49834
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 49979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 1874
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 993
telemt_me_idle_close_by_peer_total 993
telemt_me_route_drop_no_conn_total 2447663
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6490857
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 975
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 25955
telemt_desync_full_logged_total 8540
telemt_desync_suppressed_total 17415
telemt_desync_frames_bucket_total{bucket="1_2"} 6412
telemt_desync_frames_bucket_total{bucket="3_10"} 9431
telemt_desync_frames_bucket_total{bucket="gt_10"} 10112
telemt_pool_swap_total 142
telemt_pool_force_close_total 3809
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 460
telemt_me_draining_writers_reap_progress_total 45144
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3597
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41335
telemt_me_writer_teardown_success_total{mode="normal"} 46127
telemt_me_writer_teardown_noop_total 45146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.688999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 460
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 895
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 6464120
telemt_user_connections_current{user="hello"} 4570
telemt_user_octets_from_client{user="hello"} 126637290008 (117.94 GB)
telemt_user_octets_to_client{user="hello"} 3036939422264 (2.76 TB)
telemt_user_unique_ips_current{user="hello"} 1632
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 128210.1 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7634364
telemt_connections_bad_total 840334
telemt_connections_current 4447
telemt_connections_me_current 4447
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 204239
telemt_upstream_connect_attempt_total 66061
telemt_upstream_connect_success_total 65551
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 65996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_reconnect_attempts_total 6340
telemt_me_reconnect_success_total 1431
telemt_me_reader_eof_total 1285
telemt_me_idle_close_by_peer_total 1285
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2568744
telemt_me_route_drop_channel_closed_total 213
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5807081
telemt_me_endpoint_quarantine_total 1006
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 974
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
telemt_me_writers_active_current 44
telemt_desync_total 24898
telemt_desync_full_logged_total 8273
telemt_desync_suppressed_total 16625
telemt_desync_frames_bucket_total{bucket="1_2"} 6145
telemt_desync_frames_bucket_total{bucket="3_10"} 9157
telemt_desync_frames_bucket_total{bucket="gt_10"} 9596
telemt_pool_swap_total 139
telemt_pool_force_close_total 3756
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 455
telemt_me_draining_writers_reap_progress_total 43813
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3491
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40057
telemt_me_writer_teardown_success_total{mode="normal"} 45174
telemt_me_writer_teardown_noop_total 43817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88991
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.727425
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88991
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 455
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 1118
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5808185
telemt_user_connections_current{user="hello"} 4447
telemt_user_octets_from_client{user="hello"} 106595638513 (99.27 GB)
telemt_user_octets_to_client{user="hello"} 2516825541064 (2.29 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1738
telemt_user_unique_ips_recent_window{user="hello"} 564
```