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

# Server Metrics 2026-03-22 02:35:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 19774.4 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285915
telemt_connections_bad_total 19581
telemt_connections_current 825
telemt_connections_me_current 825
telemt_handshake_timeouts_total 16527
telemt_upstream_connect_attempt_total 8235
telemt_upstream_connect_success_total 8234
telemt_upstream_connect_attempts_per_request{bucket="1"} 8234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 253
telemt_me_reconnect_success_total 128
telemt_me_reader_eof_total 125
telemt_me_idle_close_by_peer_total 125
telemt_me_route_drop_no_conn_total 52489
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234532
telemt_me_endpoint_quarantine_total 164
telemt_me_single_endpoint_shadow_rotate_total 165
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
telemt_me_writers_active_current 47
telemt_desync_total 2089
telemt_desync_full_logged_total 570
telemt_desync_suppressed_total 1519
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 21
telemt_pool_force_close_total 547
telemt_me_writer_close_signal_drop_total 37
telemt_me_draining_writers_reap_progress_total 7418
telemt_me_writer_removed_unexpected_total 125
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7023
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6871
telemt_me_writer_teardown_success_total{mode="normal"} 7533
telemt_me_writer_teardown_noop_total 7419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.868857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 37
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 116
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 234138
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 2681909076 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 86817023276 (80.85 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 33140.5 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 785714
telemt_connections_bad_total 47398
telemt_connections_current 661
telemt_connections_me_current 661
telemt_handshake_timeouts_total 29004
telemt_upstream_connect_attempt_total 15350
telemt_upstream_connect_success_total 15108
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 15327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 1295
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 340638
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622636
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 267
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
telemt_me_writers_active_current 43
telemt_desync_total 2706
telemt_desync_full_logged_total 1553
telemt_desync_suppressed_total 1153
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 1029
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 35
telemt_pool_force_close_total 959
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 13605
telemt_me_writer_removed_unexpected_total 398
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1138
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12874
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 937
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12646
telemt_me_writer_teardown_success_total{mode="normal"} 14012
telemt_me_writer_teardown_noop_total 13605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.704778
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 621731
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 10202334552 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 221324819296 (206.12 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 108000.4 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7731350
telemt_connections_bad_total 629051
telemt_connections_current 1974
telemt_connections_me_current 1974
telemt_handshake_timeouts_total 254350
telemt_upstream_connect_attempt_total 39982
telemt_upstream_connect_success_total 39908
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1569
telemt_me_reconnect_success_total 809
telemt_me_reader_eof_total 818
telemt_me_idle_close_by_peer_total 818
telemt_me_route_drop_no_conn_total 4534780
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6258795
telemt_me_endpoint_quarantine_total 691
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 806
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26415
telemt_desync_full_logged_total 8741
telemt_desync_suppressed_total 17674
telemt_desync_frames_bucket_total{bucket="1_2"} 5697
telemt_desync_frames_bucket_total{bucket="3_10"} 10314
telemt_desync_frames_bucket_total{bucket="gt_10"} 10404
telemt_pool_swap_total 116
telemt_pool_force_close_total 3859
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 36489
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33781
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32630
telemt_me_writer_teardown_success_total{mode="normal"} 36820
telemt_me_writer_teardown_noop_total 36533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73353
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 158.291582
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73353
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6250946
telemt_user_connections_current{user="hello"} 1974
telemt_user_octets_from_client{user="hello"} 106279148468 (98.98 GB)
telemt_user_octets_to_client{user="hello"} 2078500476192 (1.89 TB)
telemt_user_unique_ips_current{user="hello"} 955
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 108001.8 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6380172
telemt_connections_bad_total 586787
telemt_connections_current 1647
telemt_connections_me_current 1647
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 211057
telemt_upstream_connect_attempt_total 43991
telemt_upstream_connect_success_total 43604
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1940
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 2255970
telemt_me_route_drop_channel_closed_total 259
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4769961
telemt_me_endpoint_quarantine_total 671
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 829
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22541
telemt_desync_full_logged_total 7674
telemt_desync_suppressed_total 14867
telemt_desync_frames_bucket_total{bucket="1_2"} 5429
telemt_desync_frames_bucket_total{bucket="3_10"} 8748
telemt_desync_frames_bucket_total{bucket="gt_10"} 8364
telemt_pool_swap_total 117
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 35001
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2931
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32834
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3279
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31509
telemt_me_writer_teardown_success_total{mode="normal"} 35765
telemt_me_writer_teardown_noop_total 35007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70772
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.294571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70772
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4692147
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 140174412169 (130.55 GB)
telemt_user_octets_to_client{user="hello"} 2214393395059 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 107965.8 (29h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6262684
telemt_connections_bad_total 547396
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 202773
telemt_upstream_connect_attempt_total 50146
telemt_upstream_connect_success_total 49779
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2026
telemt_me_reconnect_success_total 903
telemt_me_reader_eof_total 848
telemt_me_idle_close_by_peer_total 848
telemt_me_route_drop_no_conn_total 2149205
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4662236
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 806
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
telemt_me_writers_active_current 45
telemt_desync_total 22428
telemt_desync_full_logged_total 7543
telemt_desync_suppressed_total 14885
telemt_desync_frames_bucket_total{bucket="1_2"} 5475
telemt_desync_frames_bucket_total{bucket="3_10"} 8589
telemt_desync_frames_bucket_total{bucket="gt_10"} 8364
telemt_pool_swap_total 116
telemt_pool_force_close_total 3374
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 36170
telemt_me_writer_removed_unexpected_total 820
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3002
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34002
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32796
telemt_me_writer_teardown_success_total{mode="normal"} 37004
telemt_me_writer_teardown_noop_total 36182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.989451
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 4657862
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 133595244711 (124.42 GB)
telemt_user_octets_to_client{user="hello"} 2130127197915 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 720
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 108005.3 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20390118
telemt_connections_bad_total 1615354
telemt_connections_current 2185
telemt_connections_me_current 2185
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 605011
telemt_upstream_connect_attempt_total 195336
telemt_upstream_connect_success_total 177359
telemt_upstream_connect_fail_total 16227
telemt_upstream_connect_attempts_per_request{bucket="1"} 193586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8917
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16227
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64853
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 1448
telemt_me_idle_close_by_peer_total 1447
telemt_me_route_drop_no_conn_total 39506376
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16487803
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 847
telemt_me_single_endpoint_outage_enter_total 134
telemt_me_single_endpoint_outage_exit_total 134
telemt_me_single_endpoint_outage_reconnect_attempt_total 284
telemt_me_single_endpoint_outage_reconnect_success_total 69
telemt_me_single_endpoint_quarantine_bypass_total 284
telemt_me_single_endpoint_shadow_rotate_total 843
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 63
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
telemt_me_writers_active_current 48
telemt_desync_total 31922
telemt_desync_full_logged_total 9569
telemt_desync_suppressed_total 22353
telemt_desync_frames_bucket_total{bucket="1_2"} 6914
telemt_desync_frames_bucket_total{bucket="3_10"} 14169
telemt_desync_frames_bucket_total{bucket="gt_10"} 10839
telemt_pool_swap_total 111
telemt_pool_force_close_total 3626
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 793
telemt_me_draining_writers_reap_progress_total 33832
telemt_me_writer_removed_unexpected_total 2147
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30206
telemt_me_writer_teardown_success_total{mode="normal"} 35719
telemt_me_writer_teardown_noop_total 33858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69577
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.673378
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69577
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 793
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16617311
telemt_user_connections_current{user="hello"} 2185
telemt_user_octets_from_client{user="hello"} 217418045070 (202.49 GB)
telemt_user_octets_to_client{user="hello"} 1195147872055 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 1064
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 107972.3 (29h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6014221
telemt_connections_bad_total 564261
telemt_connections_current 1433
telemt_connections_me_current 1433
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 126248
telemt_upstream_connect_attempt_total 58758
telemt_upstream_connect_success_total 58081
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 58661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_reconnect_attempts_total 69650
telemt_me_reconnect_success_total 1787
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 2387484
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4691963
telemt_me_endpoint_quarantine_total 729
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 816
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
telemt_me_writers_active_current 43
telemt_desync_total 23342
telemt_desync_full_logged_total 8226
telemt_desync_suppressed_total 15116
telemt_desync_frames_bucket_total{bucket="1_2"} 4445
telemt_desync_frames_bucket_total{bucket="3_10"} 9043
telemt_desync_frames_bucket_total{bucket="gt_10"} 9854
telemt_pool_swap_total 111
telemt_pool_force_close_total 3201
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 37975
telemt_me_writer_removed_unexpected_total 1604
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35702
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34774
telemt_me_writer_teardown_success_total{mode="normal"} 39610
telemt_me_writer_teardown_noop_total 37976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.120161
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1498
telemt_me_writer_restored_fallback_total 34
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4684826
telemt_user_connections_current{user="hello"} 1433
telemt_user_octets_from_client{user="hello"} 124295570068 (115.76 GB)
telemt_user_octets_to_client{user="hello"} 1911836530606 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44808.2 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3909733
telemt_connections_bad_total 143087
telemt_connections_current 1292
telemt_connections_me_current 1292
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1592320
telemt_upstream_connect_attempt_total 27295
telemt_upstream_connect_success_total 27119
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 27287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 45810
telemt_me_reconnect_success_total 959
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 1020974
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1918333
telemt_me_endpoint_quarantine_total 334
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 343
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10431
telemt_desync_full_logged_total 3600
telemt_desync_suppressed_total 6831
telemt_desync_frames_bucket_total{bucket="1_2"} 1874
telemt_desync_frames_bucket_total{bucket="3_10"} 4003
telemt_desync_frames_bucket_total{bucket="gt_10"} 4554
telemt_pool_swap_total 48
telemt_pool_force_close_total 1470
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 134
telemt_me_draining_writers_reap_progress_total 16376
telemt_me_writer_removed_unexpected_total 715
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1509
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15608
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14906
telemt_me_writer_teardown_success_total{mode="normal"} 17117
telemt_me_writer_teardown_noop_total 16378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33495
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.439859
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33495
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 134
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1921956
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 53899201992 (50.20 GB)
telemt_user_octets_to_client{user="hello"} 817138100862 (761.02 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 25779.4 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195327
telemt_connections_bad_total 1646
telemt_connections_current 317
telemt_connections_me_current 317
telemt_handshake_timeouts_total 5374
telemt_upstream_connect_attempt_total 12395
telemt_upstream_connect_success_total 12365
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 162
telemt_me_reader_eof_total 166
telemt_me_idle_close_by_peer_total 166
telemt_me_route_drop_no_conn_total 53555
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172101
telemt_me_endpoint_quarantine_total 250
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1026
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 28
telemt_pool_force_close_total 625
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11168
telemt_me_writer_removed_unexpected_total 159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10608
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10543
telemt_me_writer_teardown_success_total{mode="normal"} 11334
telemt_me_writer_teardown_noop_total 11168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22502
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.974804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22502
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 148
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 171787
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 3086167356 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 104902855256 (97.70 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 107977.2 (29h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7318924
telemt_connections_bad_total 741295
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_handshake_timeouts_total 208808
telemt_upstream_connect_attempt_total 42258
telemt_upstream_connect_success_total 42102
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 42221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 1582
telemt_me_reconnect_success_total 848
telemt_me_reader_eof_total 831
telemt_me_idle_close_by_peer_total 831
telemt_me_route_drop_no_conn_total 2125926
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5475076
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 831
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
telemt_me_writers_active_current 43
telemt_desync_total 21470
telemt_desync_full_logged_total 7040
telemt_desync_suppressed_total 14430
telemt_desync_frames_bucket_total{bucket="1_2"} 5405
telemt_desync_frames_bucket_total{bucket="3_10"} 7753
telemt_desync_frames_bucket_total{bucket="gt_10"} 8312
telemt_pool_swap_total 119
telemt_pool_force_close_total 3191
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 38108
telemt_me_writer_removed_unexpected_total 802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2998
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35931
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34917
telemt_me_writer_teardown_success_total{mode="normal"} 38929
telemt_me_writer_teardown_noop_total 38110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77039
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.640709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77039
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5450117
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 109465806668 (101.95 GB)
telemt_user_octets_to_client{user="hello"} 2538866046972 (2.31 TB)
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 107973.2 (29h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6318157
telemt_connections_bad_total 624086
telemt_connections_current 1576
telemt_connections_me_current 1576
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172461
telemt_upstream_connect_attempt_total 58056
telemt_upstream_connect_success_total 57622
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 57997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_reconnect_attempts_total 5563
telemt_me_reconnect_success_total 1165
telemt_me_reader_eof_total 1051
telemt_me_idle_close_by_peer_total 1051
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2178754
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4841478
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 826
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
telemt_me_writers_active_current 46
telemt_desync_total 20073
telemt_desync_full_logged_total 6686
telemt_desync_suppressed_total 13387
telemt_desync_frames_bucket_total{bucket="1_2"} 5120
telemt_desync_frames_bucket_total{bucket="3_10"} 7320
telemt_desync_frames_bucket_total{bucket="gt_10"} 7633
telemt_pool_swap_total 117
telemt_pool_force_close_total 3153
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 36672
telemt_me_writer_removed_unexpected_total 1061
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33519
telemt_me_writer_teardown_success_total{mode="normal"} 37786
telemt_me_writer_teardown_noop_total 36676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74462
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.079470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74462
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 909
telemt_me_writer_restored_fallback_total 62
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4844531
telemt_user_connections_current{user="hello"} 1576
telemt_user_octets_from_client{user="hello"} 91447922841 (85.17 GB)
telemt_user_octets_to_client{user="hello"} 2069086858764 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 725
telemt_user_unique_ips_recent_window{user="hello"} 174
```