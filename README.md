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

# Server Metrics 2026-03-23 03:38:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 109925.6 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3749920
telemt_connections_bad_total 364247
telemt_connections_current 1121
telemt_connections_me_current 1121
telemt_handshake_timeouts_total 122817
telemt_upstream_connect_attempt_total 41041
telemt_upstream_connect_success_total 41040
telemt_upstream_connect_attempts_per_request{bucket="1"} 41040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1436
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 653
telemt_me_idle_close_by_peer_total 653
telemt_me_route_drop_no_conn_total 3017496
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3059796
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 857
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
telemt_desync_total 13103
telemt_desync_full_logged_total 4166
telemt_desync_suppressed_total 8937
telemt_desync_frames_bucket_total{bucket="1_2"} 3468
telemt_desync_frames_bucket_total{bucket="3_10"} 4796
telemt_desync_frames_bucket_total{bucket="gt_10"} 4839
telemt_pool_swap_total 122
telemt_pool_force_close_total 3689
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 37564
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2672
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35170
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33875
telemt_me_writer_teardown_success_total{mode="normal"} 37842
telemt_me_writer_teardown_noop_total 37575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.829983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3048664
telemt_user_connections_current{user="hello"} 1121
telemt_user_octets_from_client{user="hello"} 43122058868 (40.16 GB)
telemt_user_octets_to_client{user="hello"} 829703973404 (772.72 GB)
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 123291.8 (34h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4061465
telemt_connections_bad_total 377768
telemt_connections_current 573
telemt_connections_me_current 573
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102363
telemt_upstream_connect_attempt_total 77459
telemt_upstream_connect_success_total 76534
telemt_upstream_connect_fail_total 818
telemt_upstream_connect_attempts_per_request{bucket="1"} 77352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 818
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10526
telemt_me_reconnect_success_total 3757
telemt_me_reader_eof_total 3739
telemt_me_idle_close_by_peer_total 3739
telemt_me_route_drop_no_conn_total 3649641
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3223833
telemt_me_endpoint_quarantine_total 995
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 968
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
telemt_me_writers_active_current 44
telemt_desync_total 13161
telemt_desync_full_logged_total 7398
telemt_desync_suppressed_total 5763
telemt_desync_frames_bucket_total{bucket="1_2"} 2990
telemt_desync_frames_bucket_total{bucket="3_10"} 5160
telemt_desync_frames_bucket_total{bucket="gt_10"} 5011
telemt_pool_swap_total 116
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 51321
telemt_me_writer_removed_unexpected_total 3663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48098
telemt_me_writer_teardown_success_total{mode="normal"} 55023
telemt_me_writer_teardown_noop_total 51322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106345
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.695388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106345
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 265
telemt_me_writer_restored_same_endpoint_total 3330
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 3238311
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 43571289579 (40.58 GB)
telemt_user_octets_to_client{user="hello"} 805922761097 (750.57 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 198151.6 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16471961
telemt_connections_bad_total 1670097
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 400780
telemt_upstream_connect_attempt_total 89322
telemt_upstream_connect_success_total 89215
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3096
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1589
telemt_me_route_drop_no_conn_total 14068285
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13077949
telemt_me_endpoint_quarantine_total 1337
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1496
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
telemt_desync_total 54386
telemt_desync_full_logged_total 17333
telemt_desync_suppressed_total 37053
telemt_desync_frames_bucket_total{bucket="1_2"} 12118
telemt_desync_frames_bucket_total{bucket="3_10"} 21249
telemt_desync_frames_bucket_total{bucket="gt_10"} 21019
telemt_pool_swap_total 215
telemt_pool_force_close_total 6925
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1073
telemt_me_draining_writers_reap_progress_total 68362
telemt_me_writer_removed_unexpected_total 1527
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63421
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61437
telemt_me_writer_teardown_success_total{mode="normal"} 69172
telemt_me_writer_teardown_noop_total 68415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137587
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.031697
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137587
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1073
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 13077927
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 198250526401 (184.64 GB)
telemt_user_octets_to_client{user="hello"} 3532389785223 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 198153.0 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12015207
telemt_connections_bad_total 1265199
telemt_connections_current 791
telemt_connections_me_current 791
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346369
telemt_upstream_connect_attempt_total 103593
telemt_upstream_connect_success_total 102251
telemt_upstream_connect_fail_total 889
telemt_upstream_connect_attempts_per_request{bucket="1"} 103140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 889
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4557
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1822
telemt_me_idle_close_by_peer_total 1822
telemt_me_route_drop_no_conn_total 4572665
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8896645
telemt_me_endpoint_quarantine_total 1358
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1516
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39146
telemt_desync_full_logged_total 13188
telemt_desync_suppressed_total 25958
telemt_desync_frames_bucket_total{bucket="1_2"} 9695
telemt_desync_frames_bucket_total{bucket="3_10"} 15040
telemt_desync_frames_bucket_total{bucket="gt_10"} 14411
telemt_pool_swap_total 212
telemt_pool_force_close_total 6271
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66449
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62318
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60178
telemt_me_writer_teardown_success_total{mode="normal"} 68157
telemt_me_writer_teardown_noop_total 66474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134631
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.564547
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134631
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1673
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8834345
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 218542364568 (203.53 GB)
telemt_user_octets_to_client{user="hello"} 3989708744007 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 198117.0 (55h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11161658
telemt_connections_bad_total 1002454
telemt_connections_current 704
telemt_connections_me_current 704
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 347317
telemt_upstream_connect_attempt_total 88039
telemt_upstream_connect_success_total 86473
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5828
telemt_me_reconnect_success_total 2433
telemt_me_reader_eof_total 2180
telemt_me_idle_close_by_peer_total 2179
telemt_me_route_drop_no_conn_total 5350706
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8419162
telemt_me_endpoint_quarantine_total 1395
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1475
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38374
telemt_desync_full_logged_total 12725
telemt_desync_suppressed_total 25649
telemt_desync_frames_bucket_total{bucket="1_2"} 9692
telemt_desync_frames_bucket_total{bucket="3_10"} 14702
telemt_desync_frames_bucket_total{bucket="gt_10"} 13980
telemt_pool_swap_total 208
telemt_pool_force_close_total 6166
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 751
telemt_me_draining_writers_reap_progress_total 67004
telemt_me_writer_removed_unexpected_total 2326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6575
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62691
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60838
telemt_me_writer_teardown_success_total{mode="normal"} 69266
telemt_me_writer_teardown_noop_total 67075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.893484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 751
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2118
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8411053
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 193239631923 (179.97 GB)
telemt_user_octets_to_client{user="hello"} 3492368535985 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 68397.2 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11414827
telemt_connections_bad_total 673480
telemt_connections_current 1360
telemt_connections_me_current 1360
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 293028
telemt_upstream_connect_attempt_total 63284
telemt_upstream_connect_success_total 59911
telemt_upstream_connect_fail_total 2197
telemt_upstream_connect_attempts_per_request{bucket="1"} 62108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2197
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8091
telemt_me_reconnect_success_total 1409
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 25317386
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9461494
telemt_me_endpoint_quarantine_total 526
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 43
telemt_desync_total 16794
telemt_desync_full_logged_total 4615
telemt_desync_suppressed_total 12179
telemt_desync_frames_bucket_total{bucket="1_2"} 3218
telemt_desync_frames_bucket_total{bucket="3_10"} 6852
telemt_desync_frames_bucket_total{bucket="gt_10"} 6724
telemt_pool_swap_total 70
telemt_pool_force_close_total 2211
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 503
telemt_me_draining_writers_reap_progress_total 22481
telemt_me_writer_removed_unexpected_total 1292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20270
telemt_me_writer_teardown_success_total{mode="normal"} 23721
telemt_me_writer_teardown_noop_total 22500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46221
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.119390
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46221
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 503
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 910
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 9488015
telemt_user_connections_current{user="hello"} 1360
telemt_user_octets_from_client{user="hello"} 88462696618 (82.39 GB)
telemt_user_octets_to_client{user="hello"} 651234750929 (606.51 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 198123.7 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11125635
telemt_connections_bad_total 978149
telemt_connections_current 977
telemt_connections_me_current 977
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244907
telemt_upstream_connect_attempt_total 116836
telemt_upstream_connect_success_total 115641
telemt_upstream_connect_fail_total 1020
telemt_upstream_connect_attempts_per_request{bucket="1"} 116661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1020
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73218
telemt_me_reconnect_success_total 3179
telemt_me_reader_eof_total 2877
telemt_me_idle_close_by_peer_total 2874
telemt_me_route_drop_no_conn_total 5282962
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8762147
telemt_me_endpoint_quarantine_total 1350
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1502
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46662
telemt_desync_full_logged_total 16022
telemt_desync_suppressed_total 30640
telemt_desync_frames_bucket_total{bucket="1_2"} 9481
telemt_desync_frames_bucket_total{bucket="3_10"} 17872
telemt_desync_frames_bucket_total{bucket="gt_10"} 19309
telemt_pool_swap_total 204
telemt_pool_force_close_total 5887
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 71000
telemt_me_writer_removed_unexpected_total 2896
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7125
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66816
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5138
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65113
telemt_me_writer_teardown_success_total{mode="normal"} 73941
telemt_me_writer_teardown_noop_total 71001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144942
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.326227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144942
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8764999
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 196813693329 (183.30 GB)
telemt_user_octets_to_client{user="hello"} 3350478941908 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 134960.0 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11852134
telemt_connections_bad_total 486917
telemt_connections_current 769
telemt_connections_me_current 769
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4797500
telemt_upstream_connect_attempt_total 65596
telemt_upstream_connect_success_total 65123
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 65583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_reconnect_attempts_total 49205
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 4109592
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5693374
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1040
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31961
telemt_desync_full_logged_total 10930
telemt_desync_suppressed_total 21031
telemt_desync_frames_bucket_total{bucket="1_2"} 6384
telemt_desync_frames_bucket_total{bucket="3_10"} 12605
telemt_desync_frames_bucket_total{bucket="gt_10"} 12972
telemt_pool_swap_total 143
telemt_pool_force_close_total 4087
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 50685
telemt_me_writer_removed_unexpected_total 1643
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4068
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3643
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46598
telemt_me_writer_teardown_success_total{mode="normal"} 52379
telemt_me_writer_teardown_noop_total 50692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.760458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 2747
telemt_me_writer_restored_same_endpoint_total 1699
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5685439
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 120621740096 (112.34 GB)
telemt_user_octets_to_client{user="hello"} 2213259590354 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 115930.7 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1594444
telemt_connections_bad_total 37019
telemt_connections_current 614
telemt_connections_me_current 614
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32753
telemt_upstream_connect_attempt_total 54879
telemt_upstream_connect_success_total 54709
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 54851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 810
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2370
telemt_me_reconnect_success_total 967
telemt_me_reader_eof_total 959
telemt_me_idle_close_by_peer_total 959
telemt_me_route_drop_no_conn_total 534263
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1416619
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 959
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
telemt_me_writers_active_current 44
telemt_desync_total 9945
telemt_desync_full_logged_total 2807
telemt_desync_suppressed_total 7138
telemt_desync_frames_bucket_total{bucket="1_2"} 3110
telemt_desync_frames_bucket_total{bucket="3_10"} 3759
telemt_desync_frames_bucket_total{bucket="gt_10"} 3076
telemt_pool_swap_total 125
telemt_pool_force_close_total 3148
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 46713
telemt_me_writer_removed_unexpected_total 923
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44155
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3060
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43565
telemt_me_writer_teardown_success_total{mode="normal"} 47679
telemt_me_writer_teardown_noop_total 46717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94396
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.507795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94396
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1412318
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 26628140745 (24.80 GB)
telemt_user_octets_to_client{user="hello"} 593671291883 (552.90 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 198128.3 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13430861
telemt_connections_bad_total 1627403
telemt_connections_current 977
telemt_connections_me_current 977
telemt_handshake_timeouts_total 392034
telemt_upstream_connect_attempt_total 79563
telemt_upstream_connect_success_total 79206
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 79427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3096
telemt_me_reconnect_success_total 1570
telemt_me_reader_eof_total 1557
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 4496803
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10116169
telemt_me_endpoint_quarantine_total 1457
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1503
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
telemt_me_writers_active_current 44
telemt_desync_total 42468
telemt_desync_full_logged_total 13870
telemt_desync_suppressed_total 28598
telemt_desync_frames_bucket_total{bucket="1_2"} 10340
telemt_desync_frames_bucket_total{bucket="3_10"} 15600
telemt_desync_frames_bucket_total{bucket="gt_10"} 16528
telemt_pool_swap_total 220
telemt_pool_force_close_total 5746
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 71993
telemt_me_writer_removed_unexpected_total 1491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67970
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5572
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66247
telemt_me_writer_teardown_success_total{mode="normal"} 73540
telemt_me_writer_teardown_noop_total 71995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145535
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.882803
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145535
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10082789
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 195464149152 (182.04 GB)
telemt_user_octets_to_client{user="hello"} 4484753594528 (4.08 TB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 198124.9 (55h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11746159
telemt_connections_bad_total 1377777
telemt_connections_current 738
telemt_connections_me_current 738
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 314905
telemt_upstream_connect_attempt_total 107237
telemt_upstream_connect_success_total 106310
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 107029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10826
telemt_me_reconnect_success_total 2682
telemt_me_reader_eof_total 2489
telemt_me_idle_close_by_peer_total 2488
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5665184
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9034938
telemt_me_endpoint_quarantine_total 1630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1506
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42136
telemt_desync_full_logged_total 13569
telemt_desync_suppressed_total 28567
telemt_desync_frames_bucket_total{bucket="1_2"} 10949
telemt_desync_frames_bucket_total{bucket="3_10"} 15483
telemt_desync_frames_bucket_total{bucket="gt_10"} 15704
telemt_pool_swap_total 210
telemt_pool_force_close_total 5511
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 72197
telemt_me_writer_removed_unexpected_total 2525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67878
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66686
telemt_me_writer_teardown_success_total{mode="normal"} 74819
telemt_me_writer_teardown_noop_total 72202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.590032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9039487
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 158055000352 (147.20 GB)
telemt_user_octets_to_client{user="hello"} 3526781031758 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 82
```