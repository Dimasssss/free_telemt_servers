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

# Server Metrics 2026-03-22 07:37:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 37874.0 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802229
telemt_connections_bad_total 50469
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_handshake_timeouts_total 38251
telemt_upstream_connect_attempt_total 15320
telemt_upstream_connect_success_total 15317
telemt_upstream_connect_attempts_per_request{bucket="1"} 15317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 427
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 311516
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664726
telemt_me_endpoint_quarantine_total 269
telemt_me_single_endpoint_shadow_rotate_total 306
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 31
telemt_desync_total 5299
telemt_desync_full_logged_total 1499
telemt_desync_suppressed_total 3800
telemt_desync_frames_bucket_total{bucket="1_2"} 1683
telemt_desync_frames_bucket_total{bucket="3_10"} 1985
telemt_desync_frames_bucket_total{bucket="gt_10"} 1631
telemt_pool_swap_total 41
telemt_pool_force_close_total 1120
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 13862
telemt_me_writer_removed_unexpected_total 233
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 957
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13113
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12742
telemt_me_writer_teardown_success_total{mode="normal"} 14070
telemt_me_writer_teardown_noop_total 13863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27933
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.029569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27933
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 663520
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 9054939152 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 226392649960 (210.84 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 51240.4 (14h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284986
telemt_connections_bad_total 123940
telemt_connections_current 1502
telemt_connections_me_current 1502
telemt_handshake_timeouts_total 39773
telemt_upstream_connect_attempt_total 26815
telemt_upstream_connect_success_total 26418
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 26764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1985
telemt_me_reconnect_success_total 813
telemt_me_reader_eof_total 703
telemt_me_idle_close_by_peer_total 703
telemt_me_route_drop_no_conn_total 496512
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 969269
telemt_me_endpoint_quarantine_total 469
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 409
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
telemt_me_writers_active_current 49
telemt_desync_total 4193
telemt_desync_full_logged_total 2451
telemt_desync_suppressed_total 1742
telemt_desync_frames_bucket_total{bucket="1_2"} 896
telemt_desync_frames_bucket_total{bucket="3_10"} 1621
telemt_desync_frames_bucket_total{bucket="gt_10"} 1676
telemt_pool_swap_total 54
telemt_pool_force_close_total 1450
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 20938
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19729
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19488
telemt_me_writer_teardown_success_total{mode="normal"} 21600
telemt_me_writer_teardown_noop_total 20938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42538
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.385907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42538
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 619
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 970955
telemt_user_connections_current{user="hello"} 1502
telemt_user_octets_from_client{user="hello"} 15268105694 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 351792840071 (327.63 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 126100.3 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9155845
telemt_connections_bad_total 838509
telemt_connections_current 4878
telemt_connections_me_current 4878
telemt_handshake_timeouts_total 283814
telemt_upstream_connect_attempt_total 46566
telemt_upstream_connect_success_total 46485
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 923
telemt_me_reader_eof_total 925
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 4978335
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7203561
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 945
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
telemt_me_writers_active_current 50
telemt_me_writers_warm_current 34
telemt_desync_total 31285
telemt_desync_full_logged_total 10338
telemt_desync_suppressed_total 20947
telemt_desync_frames_bucket_total{bucket="1_2"} 6805
telemt_desync_frames_bucket_total{bucket="3_10"} 12142
telemt_desync_frames_bucket_total{bucket="gt_10"} 12338
telemt_pool_swap_total 136
telemt_pool_force_close_total 4487
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 42474
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3520
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 270
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37987
telemt_me_writer_teardown_success_total{mode="normal"} 42853
telemt_me_writer_teardown_noop_total 42518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.978559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 7194173
telemt_user_connections_current{user="hello"} 4878
telemt_user_octets_from_client{user="hello"} 120693325348 (112.40 GB)
telemt_user_octets_to_client{user="hello"} 2450607656900 (2.23 TB)
telemt_user_unique_ips_current{user="hello"} 1929
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 126101.6 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7526598
telemt_connections_bad_total 665486
telemt_connections_current 4169
telemt_connections_me_current 4169
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 245828
telemt_upstream_connect_attempt_total 50531
telemt_upstream_connect_success_total 50124
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 50334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 562
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2632
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 958
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 2523543
telemt_me_route_drop_channel_closed_total 307
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5577984
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 968
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 40
telemt_desync_total 25676
telemt_desync_full_logged_total 8802
telemt_desync_suppressed_total 16874
telemt_desync_frames_bucket_total{bucket="1_2"} 6132
telemt_desync_frames_bucket_total{bucket="3_10"} 9961
telemt_desync_frames_bucket_total{bucket="gt_10"} 9583
telemt_pool_swap_total 137
telemt_pool_force_close_total 4105
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 40903
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3389
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38367
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36798
telemt_me_writer_teardown_success_total{mode="normal"} 41756
telemt_me_writer_teardown_noop_total 40909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82665
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.486888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82665
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 867
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5498906
telemt_user_connections_current{user="hello"} 4169
telemt_user_octets_from_client{user="hello"} 155810861137 (145.11 GB)
telemt_user_octets_to_client{user="hello"} 2661037458051 (2.42 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1650
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 126065.8 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7273543
telemt_connections_bad_total 599775
telemt_connections_current 3621
telemt_connections_me_current 3621
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241676
telemt_upstream_connect_attempt_total 57153
telemt_upstream_connect_success_total 56486
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2736
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1097
telemt_me_idle_close_by_peer_total 1097
telemt_me_route_drop_no_conn_total 2931792
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5429216
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 930
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_me_writers_warm_current 25
telemt_desync_total 25290
telemt_desync_full_logged_total 8635
telemt_desync_suppressed_total 16655
telemt_desync_frames_bucket_total{bucket="1_2"} 6140
telemt_desync_frames_bucket_total{bucket="3_10"} 9713
telemt_desync_frames_bucket_total{bucket="gt_10"} 9437
telemt_pool_swap_total 134
telemt_pool_force_close_total 3955
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 456
telemt_me_draining_writers_reap_progress_total 41851
telemt_me_writer_removed_unexpected_total 1107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39254
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 293
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37896
telemt_me_writer_teardown_success_total{mode="normal"} 42962
telemt_me_writer_teardown_noop_total 41863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84825
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.684216
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84825
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 456
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5422691
telemt_user_connections_current{user="hello"} 3621
telemt_user_octets_from_client{user="hello"} 143773369099 (133.90 GB)
telemt_user_octets_to_client{user="hello"} 2416484884199 (2.20 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1514
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 126105.0 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23303756
telemt_connections_bad_total 1936904
telemt_connections_current 5457
telemt_connections_me_current 5457
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 683568
telemt_upstream_connect_attempt_total 240793
telemt_upstream_connect_success_total 221055
telemt_upstream_connect_fail_total 17756
telemt_upstream_connect_attempts_per_request{bucket="1"} 238811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17756
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 66507
telemt_me_reconnect_success_total 2687
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 44587376
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18792740
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 985
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 991
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 36304
telemt_desync_full_logged_total 10818
telemt_desync_suppressed_total 25486
telemt_desync_frames_bucket_total{bucket="1_2"} 8016
telemt_desync_frames_bucket_total{bucket="3_10"} 16059
telemt_desync_frames_bucket_total{bucket="gt_10"} 12229
telemt_pool_swap_total 131
telemt_pool_force_close_total 4123
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 955
telemt_me_draining_writers_reap_progress_total 39338
telemt_me_writer_removed_unexpected_total 2490
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 589
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35215
telemt_me_writer_teardown_success_total{mode="normal"} 41559
telemt_me_writer_teardown_noop_total 39370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 281.709137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 955
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 18958568
telemt_user_connections_current{user="hello"} 5457
telemt_user_octets_from_client{user="hello"} 273991973799 (255.17 GB)
telemt_user_octets_to_client{user="hello"} 1414361108739 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2006
telemt_user_unique_ips_recent_window{user="hello"} 1135
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 126072.5 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6934955
telemt_connections_bad_total 635687
telemt_connections_current 3932
telemt_connections_me_current 3932
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 143658
telemt_upstream_connect_attempt_total 65554
telemt_upstream_connect_success_total 64807
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 65448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_reconnect_attempts_total 70053
telemt_me_reconnect_success_total 1932
telemt_me_reader_eof_total 1709
telemt_me_idle_close_by_peer_total 1708
telemt_me_route_drop_no_conn_total 2666299
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5431266
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 955
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_warm_current 24
telemt_desync_total 27338
telemt_desync_full_logged_total 9527
telemt_desync_suppressed_total 17811
telemt_desync_frames_bucket_total{bucket="1_2"} 5462
telemt_desync_frames_bucket_total{bucket="3_10"} 10515
telemt_desync_frames_bucket_total{bucket="gt_10"} 11361
telemt_pool_swap_total 131
telemt_pool_force_close_total 3766
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 444
telemt_me_draining_writers_reap_progress_total 44039
telemt_me_writer_removed_unexpected_total 1740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4409
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3348
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40273
telemt_me_writer_teardown_success_total{mode="normal"} 45816
telemt_me_writer_teardown_noop_total 44040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89856
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.042098
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89856
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 444
telemt_me_refill_failed_total 4219
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5422390
telemt_user_connections_current{user="hello"} 3932
telemt_user_octets_from_client{user="hello"} 137900627708 (128.43 GB)
telemt_user_octets_to_client{user="hello"} 2268099697474 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1696
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 62908.5 (17h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5235987
telemt_connections_bad_total 211053
telemt_connections_current 3558
telemt_connections_me_current 3558
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2085126
telemt_upstream_connect_attempt_total 34463
telemt_upstream_connect_success_total 34224
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 34456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_reconnect_attempts_total 46243
telemt_me_reconnect_success_total 1084
telemt_me_reader_eof_total 774
telemt_me_idle_close_by_peer_total 774
telemt_me_route_drop_no_conn_total 1279316
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2605718
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 483
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
telemt_desync_total 13927
telemt_desync_full_logged_total 4789
telemt_desync_suppressed_total 9138
telemt_desync_frames_bucket_total{bucket="1_2"} 2750
telemt_desync_frames_bucket_total{bucket="3_10"} 5326
telemt_desync_frames_bucket_total{bucket="gt_10"} 5851
telemt_pool_swap_total 68
telemt_pool_force_close_total 2002
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 182
telemt_me_draining_writers_reap_progress_total 22801
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21749
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1772
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20799
telemt_me_writer_teardown_success_total{mode="normal"} 23667
telemt_me_writer_teardown_noop_total 22803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46470
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.160264
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46470
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 182
telemt_me_refill_failed_total 2623
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2607335
telemt_user_connections_current{user="hello"} 3558
telemt_user_octets_from_client{user="hello"} 66294600820 (61.74 GB)
telemt_user_octets_to_client{user="hello"} 1157570315870 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1517
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 43879.3 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348405
telemt_connections_bad_total 2451
telemt_connections_current 826
telemt_connections_me_current 826
telemt_handshake_timeouts_total 7658
telemt_upstream_connect_attempt_total 20935
telemt_upstream_connect_success_total 20881
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 20931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 905
telemt_me_reconnect_success_total 308
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 107583
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316089
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 380
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1494
telemt_desync_full_logged_total 424
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 48
telemt_pool_force_close_total 1086
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 18923
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17990
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17837
telemt_me_writer_teardown_success_total{mode="normal"} 19227
telemt_me_writer_teardown_noop_total 18923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38150
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.589259
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38150
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 315543
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 5368592616 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 175138093248 (163.11 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 126077.1 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8492404
telemt_connections_bad_total 924630
telemt_connections_current 4233
telemt_connections_me_current 4233
telemt_handshake_timeouts_total 238550
telemt_upstream_connect_attempt_total 49350
telemt_upstream_connect_success_total 49169
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1835
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 975
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 2380714
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6305417
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 959
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 27
telemt_desync_total 25201
telemt_desync_full_logged_total 8277
telemt_desync_suppressed_total 16924
telemt_desync_frames_bucket_total{bucket="1_2"} 6264
telemt_desync_frames_bucket_total{bucket="3_10"} 9165
telemt_desync_frames_bucket_total{bucket="gt_10"} 9772
telemt_pool_swap_total 139
telemt_pool_force_close_total 3716
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 443
telemt_me_draining_writers_reap_progress_total 44501
telemt_me_writer_removed_unexpected_total 937
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41951
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40785
telemt_me_writer_teardown_success_total{mode="normal"} 45466
telemt_me_writer_teardown_noop_total 44503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.497219
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 443
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6279179
telemt_user_connections_current{user="hello"} 4233
telemt_user_octets_from_client{user="hello"} 124047873460 (115.53 GB)
telemt_user_octets_to_client{user="hello"} 2946806808184 (2.68 TB)
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 126073.6 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7411243
telemt_connections_bad_total 796156
telemt_connections_current 3984
telemt_connections_me_current 3984
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 198746
telemt_upstream_connect_attempt_total 65336
telemt_upstream_connect_success_total 64839
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 65273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_reconnect_attempts_total 6024
telemt_me_reconnect_success_total 1391
telemt_me_reader_eof_total 1254
telemt_me_idle_close_by_peer_total 1254
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2482058
telemt_me_route_drop_channel_closed_total 202
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5641503
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 959
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
telemt_me_writers_warm_current 26
telemt_desync_total 24143
telemt_desync_full_logged_total 8029
telemt_desync_suppressed_total 16114
telemt_desync_frames_bucket_total{bucket="1_2"} 5961
telemt_desync_frames_bucket_total{bucket="3_10"} 8863
telemt_desync_frames_bucket_total{bucket="gt_10"} 9319
telemt_pool_swap_total 136
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 443
telemt_me_draining_writers_reap_progress_total 43139
telemt_me_writer_removed_unexpected_total 1269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39477
telemt_me_writer_teardown_success_total{mode="normal"} 44469
telemt_me_writer_teardown_noop_total 43143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87612
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.577880
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87612
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 443
telemt_me_refill_failed_total 267
telemt_me_writer_restored_same_endpoint_total 1089
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5643104
telemt_user_connections_current{user="hello"} 3984
telemt_user_octets_from_client{user="hello"} 104288461409 (97.13 GB)
telemt_user_octets_to_client{user="hello"} 2453523652920 (2.23 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1665
telemt_user_unique_ips_recent_window{user="hello"} 541
```