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

# Server Metrics 2026-03-22 20:09:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83015.8 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3085389
telemt_connections_bad_total 211780
telemt_connections_current 1111
telemt_connections_me_current 1111
telemt_handshake_timeouts_total 98563
telemt_upstream_connect_attempt_total 30466
telemt_upstream_connect_success_total 30465
telemt_upstream_connect_attempts_per_request{bucket="1"} 30465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1216
telemt_me_reconnect_success_total 513
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_route_drop_no_conn_total 2774855
telemt_me_route_drop_channel_closed_total 1101
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2610608
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 563
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 643
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
telemt_me_writers_active_current 43
telemt_desync_total 11178
telemt_desync_full_logged_total 3540
telemt_desync_suppressed_total 7638
telemt_desync_frames_bucket_total{bucket="1_2"} 2992
telemt_desync_frames_bucket_total{bucket="3_10"} 4142
telemt_desync_frames_bucket_total{bucket="gt_10"} 4044
telemt_pool_swap_total 92
telemt_pool_force_close_total 2877
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 591
telemt_me_draining_writers_reap_progress_total 27880
telemt_me_writer_removed_unexpected_total 504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2032
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26056
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25003
telemt_me_writer_teardown_success_total{mode="normal"} 28088
telemt_me_writer_teardown_noop_total 27891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55979
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 320.012268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55979
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 591
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2602295
telemt_user_connections_current{user="hello"} 1111
telemt_user_octets_from_client{user="hello"} 38312300896 (35.68 GB)
telemt_user_octets_to_client{user="hello"} 684684376696 (637.66 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 96381.9 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3842740
telemt_connections_bad_total 340483
telemt_connections_current 874
telemt_connections_me_current 874
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97804
telemt_upstream_connect_attempt_total 58453
telemt_upstream_connect_success_total 57734
telemt_upstream_connect_fail_total 634
telemt_upstream_connect_attempts_per_request{bucket="1"} 58368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 634
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6811
telemt_me_reconnect_success_total 2652
telemt_me_reader_eof_total 2602
telemt_me_idle_close_by_peer_total 2602
telemt_me_route_drop_no_conn_total 3608600
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3060696
telemt_me_endpoint_quarantine_total 734
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 741
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 28
telemt_desync_total 12272
telemt_desync_full_logged_total 6859
telemt_desync_suppressed_total 5413
telemt_desync_frames_bucket_total{bucket="1_2"} 2805
telemt_desync_frames_bucket_total{bucket="3_10"} 4810
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 89
telemt_pool_force_close_total 2722
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 230
telemt_me_draining_writers_reap_progress_total 38372
telemt_me_writer_removed_unexpected_total 2547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4729
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36208
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35650
telemt_me_writer_teardown_success_total{mode="normal"} 40937
telemt_me_writer_teardown_noop_total 38373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.144828
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 230
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2339
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3071460
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 40166906047 (37.41 GB)
telemt_user_octets_to_client{user="hello"} 734862739054 (684.39 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 171241.9 (47h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15967364
telemt_connections_bad_total 1548088
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392972
telemt_upstream_connect_attempt_total 76103
telemt_upstream_connect_success_total 76006
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2809
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1387
telemt_me_route_drop_no_conn_total 13979699
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12722130
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1277
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 52516
telemt_desync_full_logged_total 16533
telemt_desync_suppressed_total 35983
telemt_desync_frames_bucket_total{bucket="1_2"} 11710
telemt_desync_frames_bucket_total{bucket="3_10"} 20457
telemt_desync_frames_bucket_total{bucket="gt_10"} 20349
telemt_pool_swap_total 185
telemt_pool_force_close_total 6251
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1018
telemt_me_draining_writers_reap_progress_total 56265
telemt_me_writer_removed_unexpected_total 1341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4930
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50014
telemt_me_writer_teardown_success_total{mode="normal"} 56883
telemt_me_writer_teardown_noop_total 56316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.722227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1018
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1248
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12722591
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 186090171957 (173.31 GB)
telemt_user_octets_to_client{user="hello"} 3387605756815 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 171243.9 (47h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11549126
telemt_connections_bad_total 1155971
telemt_connections_current 1118
telemt_connections_me_current 1118
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342932
telemt_upstream_connect_attempt_total 88630
telemt_upstream_connect_success_total 87375
telemt_upstream_connect_fail_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 88225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3716
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 850
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4157
telemt_me_reconnect_success_total 1737
telemt_me_reader_eof_total 1603
telemt_me_idle_close_by_peer_total 1603
telemt_me_route_drop_no_conn_total 4499844
telemt_me_route_drop_channel_closed_total 495
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8604436
telemt_me_endpoint_quarantine_total 1084
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1298
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
telemt_me_writers_active_current 44
telemt_desync_total 38178
telemt_desync_full_logged_total 12844
telemt_desync_suppressed_total 25334
telemt_desync_frames_bucket_total{bucket="1_2"} 9415
telemt_desync_frames_bucket_total{bucket="3_10"} 14691
telemt_desync_frames_bucket_total{bucket="gt_10"} 14072
telemt_pool_swap_total 182
telemt_pool_force_close_total 5636
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54690
telemt_me_writer_removed_unexpected_total 1641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 506
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49054
telemt_me_writer_teardown_success_total{mode="normal"} 56178
telemt_me_writer_teardown_noop_total 54715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.710743
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1483
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8542551
telemt_user_connections_current{user="hello"} 1118
telemt_user_octets_from_client{user="hello"} 214789070997 (200.04 GB)
telemt_user_octets_to_client{user="hello"} 3861411780086 (3.51 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 171207.2 (47h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10831314
telemt_connections_bad_total 937773
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343939
telemt_upstream_connect_attempt_total 73718
telemt_upstream_connect_success_total 72583
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 5010
telemt_me_reconnect_success_total 2020
telemt_me_reader_eof_total 1766
telemt_me_idle_close_by_peer_total 1765
telemt_me_route_drop_no_conn_total 5265551
telemt_me_route_drop_channel_closed_total 375
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8191738
telemt_me_endpoint_quarantine_total 1163
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1253
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 37546
telemt_desync_full_logged_total 12427
telemt_desync_suppressed_total 25119
telemt_desync_frames_bucket_total{bucket="1_2"} 9494
telemt_desync_frames_bucket_total{bucket="3_10"} 14351
telemt_desync_frames_bucket_total{bucket="gt_10"} 13701
telemt_pool_swap_total 180
telemt_pool_force_close_total 5581
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 54786
telemt_me_writer_removed_unexpected_total 1908
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5509
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51104
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49205
telemt_me_writer_teardown_success_total{mode="normal"} 56613
telemt_me_writer_teardown_noop_total 54857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111470
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.994611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111470
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 1739
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8183988
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 190958630565 (177.84 GB)
telemt_user_octets_to_client{user="hello"} 3407161793413 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41487.6 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10835057
telemt_connections_bad_total 658602
telemt_connections_current 1769
telemt_connections_me_current 1769
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 234563
telemt_upstream_connect_attempt_total 45406
telemt_upstream_connect_success_total 43134
telemt_upstream_connect_fail_total 1558
telemt_upstream_connect_attempts_per_request{bucket="1"} 44692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5963
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1558
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6540
telemt_me_reconnect_success_total 911
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 25203416
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8999307
telemt_me_endpoint_quarantine_total 261
telemt_me_single_endpoint_outage_enter_total 65
telemt_me_single_endpoint_outage_exit_total 65
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 320
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
telemt_me_writers_warm_current 26
telemt_desync_total 14645
telemt_desync_full_logged_total 3866
telemt_desync_suppressed_total 10779
telemt_desync_frames_bucket_total{bucket="1_2"} 2708
telemt_desync_frames_bucket_total{bucket="3_10"} 5961
telemt_desync_frames_bucket_total{bucket="gt_10"} 5976
telemt_pool_swap_total 41
telemt_pool_force_close_total 1507
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 434
telemt_me_draining_writers_reap_progress_total 11814
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10820
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10307
telemt_me_writer_teardown_success_total{mode="normal"} 12576
telemt_me_writer_teardown_noop_total 11833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24409
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.378931
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24409
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 434
telemt_me_refill_failed_total 311
telemt_me_writer_restored_same_endpoint_total 613
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 9021403
telemt_user_connections_current{user="hello"} 1769
telemt_user_octets_from_client{user="hello"} 82445808343 (76.78 GB)
telemt_user_octets_to_client{user="hello"} 497297610383 (463.14 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 171213.9 (47h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10717925
telemt_connections_bad_total 907007
telemt_connections_current 1115
telemt_connections_me_current 1115
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 235828
telemt_upstream_connect_attempt_total 103175
telemt_upstream_connect_success_total 102087
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 103016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1340
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72385
telemt_me_reconnect_success_total 2826
telemt_me_reader_eof_total 2516
telemt_me_idle_close_by_peer_total 2514
telemt_me_route_drop_no_conn_total 5200778
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8464103
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1280
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
telemt_me_writers_active_current 45
telemt_desync_total 45054
telemt_desync_full_logged_total 15351
telemt_desync_suppressed_total 29703
telemt_desync_frames_bucket_total{bucket="1_2"} 9133
telemt_desync_frames_bucket_total{bucket="3_10"} 17260
telemt_desync_frames_bucket_total{bucket="gt_10"} 18661
telemt_pool_swap_total 175
telemt_pool_force_close_total 5229
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 58710
telemt_me_writer_removed_unexpected_total 2554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6242
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53481
telemt_me_writer_teardown_success_total{mode="normal"} 61290
telemt_me_writer_teardown_noop_total 58711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120001
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.052069
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120001
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2375
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8467356
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 191815933745 (178.64 GB)
telemt_user_octets_to_client{user="hello"} 3218855518200 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 108050.1 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11306787
telemt_connections_bad_total 451697
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4653076
telemt_upstream_connect_attempt_total 51214
telemt_upstream_connect_success_total 50833
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 51205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_reconnect_attempts_total 48492
telemt_me_reconnect_success_total 1674
telemt_me_reader_eof_total 1331
telemt_me_idle_close_by_peer_total 1330
telemt_me_route_drop_no_conn_total 4039133
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5445299
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 812
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 14
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30597
telemt_desync_full_logged_total 10366
telemt_desync_suppressed_total 20231
telemt_desync_frames_bucket_total{bucket="1_2"} 6098
telemt_desync_frames_bucket_total{bucket="3_10"} 12108
telemt_desync_frames_bucket_total{bucket="gt_10"} 12391
telemt_pool_swap_total 113
telemt_pool_force_close_total 3456
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 351
telemt_me_draining_writers_reap_progress_total 37591
telemt_me_writer_removed_unexpected_total 1391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3324
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34135
telemt_me_writer_teardown_success_total{mode="normal"} 39016
telemt_me_writer_teardown_noop_total 37598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.475420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 351
telemt_me_refill_failed_total 2721
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5438156
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 117209119764 (109.16 GB)
telemt_user_octets_to_client{user="hello"} 2082789610382 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 89020.7 (24h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1341058
telemt_connections_bad_total 30213
telemt_connections_current 1004
telemt_connections_me_current 1004
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25128
telemt_upstream_connect_attempt_total 42127
telemt_upstream_connect_success_total 42001
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 42100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 718
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1939
telemt_me_reconnect_success_total 809
telemt_me_reader_eof_total 787
telemt_me_idle_close_by_peer_total 787
telemt_me_route_drop_no_conn_total 469277
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1190541
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 732
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
telemt_desync_total 7146
telemt_desync_full_logged_total 2213
telemt_desync_suppressed_total 4933
telemt_desync_frames_bucket_total{bucket="1_2"} 1578
telemt_desync_frames_bucket_total{bucket="3_10"} 2814
telemt_desync_frames_bucket_total{bucket="gt_10"} 2754
telemt_pool_swap_total 95
telemt_pool_force_close_total 2460
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 35091
telemt_me_writer_removed_unexpected_total 759
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33119
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32631
telemt_me_writer_teardown_success_total{mode="normal"} 35881
telemt_me_writer_teardown_noop_total 35095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70976
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.378558
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70976
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1186627
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 22883145109 (21.31 GB)
telemt_user_octets_to_client{user="hello"} 502404672787 (467.90 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 171218.4 (47h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13031356
telemt_connections_bad_total 1520672
telemt_connections_current 1523
telemt_connections_me_current 1523
telemt_handshake_timeouts_total 373546
telemt_upstream_connect_attempt_total 64684
telemt_upstream_connect_success_total 64352
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2536
telemt_me_reconnect_success_total 1329
telemt_me_reader_eof_total 1295
telemt_me_idle_close_by_peer_total 1295
telemt_me_route_drop_no_conn_total 4421309
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9863323
telemt_me_endpoint_quarantine_total 1150
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1280
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 40869
telemt_desync_full_logged_total 13324
telemt_desync_suppressed_total 27545
telemt_desync_frames_bucket_total{bucket="1_2"} 9761
telemt_desync_frames_bucket_total{bucket="3_10"} 15079
telemt_desync_frames_bucket_total{bucket="gt_10"} 16029
telemt_pool_swap_total 190
telemt_pool_force_close_total 5225
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 58277
telemt_me_writer_removed_unexpected_total 1246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54798
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53052
telemt_me_writer_teardown_success_total{mode="normal"} 59562
telemt_me_writer_teardown_noop_total 58279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.462364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1162
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 9830985
telemt_user_connections_current{user="hello"} 1523
telemt_user_octets_from_client{user="hello"} 192116129280 (178.92 GB)
telemt_user_octets_to_client{user="hello"} 4342916369480 (3.95 TB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 171215.2 (47h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11333240
telemt_connections_bad_total 1283005
telemt_connections_current 1286
telemt_connections_me_current 1286
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 298224
telemt_upstream_connect_attempt_total 91134
telemt_upstream_connect_success_total 90311
telemt_upstream_connect_fail_total 617
telemt_upstream_connect_attempts_per_request{bucket="1"} 90928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 617
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9803
telemt_me_reconnect_success_total 2347
telemt_me_reader_eof_total 2195
telemt_me_idle_close_by_peer_total 2194
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5596109
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8762703
telemt_me_endpoint_quarantine_total 1307
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1283
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
telemt_me_writers_active_current 44
telemt_desync_total 40020
telemt_desync_full_logged_total 12927
telemt_desync_suppressed_total 27093
telemt_desync_frames_bucket_total{bucket="1_2"} 9986
telemt_desync_frames_bucket_total{bucket="3_10"} 14875
telemt_desync_frames_bucket_total{bucket="gt_10"} 15159
telemt_pool_swap_total 180
telemt_pool_force_close_total 5023
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 58081
telemt_me_writer_removed_unexpected_total 2226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54284
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53058
telemt_me_writer_teardown_success_total{mode="normal"} 60383
telemt_me_writer_teardown_noop_total 58086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118469
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.177273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118469
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 385
telemt_me_writer_restored_same_endpoint_total 1914
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 8768251
telemt_user_connections_current{user="hello"} 1286
telemt_user_octets_from_client{user="hello"} 155243321717 (144.58 GB)
telemt_user_octets_to_client{user="hello"} 3392512621563 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 392
```