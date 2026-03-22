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

# Server Metrics 2026-03-22 16:04:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 68263.2 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2399897
telemt_connections_bad_total 128638
telemt_connections_current 1639
telemt_connections_me_current 1639
telemt_handshake_timeouts_total 86807
telemt_upstream_connect_attempt_total 25246
telemt_upstream_connect_success_total 25245
telemt_upstream_connect_attempts_per_request{bucket="1"} 25245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1027
telemt_me_reconnect_success_total 434
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 1926396
telemt_me_route_drop_channel_closed_total 783
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2041067
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 533
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 9984
telemt_desync_full_logged_total 3102
telemt_desync_suppressed_total 6882
telemt_desync_frames_bucket_total{bucket="1_2"} 2665
telemt_desync_frames_bucket_total{bucket="3_10"} 3748
telemt_desync_frames_bucket_total{bucket="gt_10"} 3571
telemt_pool_swap_total 75
telemt_pool_force_close_total 2318
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 23056
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1676
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2271
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20738
telemt_me_writer_teardown_success_total{mode="normal"} 23265
telemt_me_writer_teardown_noop_total 23062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46327
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 207.874638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46327
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2037679
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 30993485276 (28.86 GB)
telemt_user_octets_to_client{user="hello"} 545774960452 (508.29 GB)
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 81629.8 (22h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3571094
telemt_connections_bad_total 325807
telemt_connections_current 1320
telemt_connections_me_current 1320
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 87096
telemt_upstream_connect_attempt_total 51597
telemt_upstream_connect_success_total 50970
telemt_upstream_connect_fail_total 555
telemt_upstream_connect_attempts_per_request{bucket="1"} 51525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 555
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6049
telemt_me_reconnect_success_total 2187
telemt_me_reader_eof_total 2130
telemt_me_idle_close_by_peer_total 2130
telemt_me_route_drop_no_conn_total 3523312
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2828962
telemt_me_endpoint_quarantine_total 659
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 630
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
telemt_me_writers_active_current 43
telemt_desync_total 10995
telemt_desync_full_logged_total 6127
telemt_desync_suppressed_total 4868
telemt_desync_frames_bucket_total{bucket="1_2"} 2568
telemt_desync_frames_bucket_total{bucket="3_10"} 4321
telemt_desync_frames_bucket_total{bucket="gt_10"} 4106
telemt_pool_swap_total 76
telemt_pool_force_close_total 2291
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 32582
telemt_me_writer_removed_unexpected_total 2085
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3943
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30730
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30291
telemt_me_writer_teardown_success_total{mode="normal"} 34673
telemt_me_writer_teardown_noop_total 32582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67255
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.173529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67255
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 2840260
telemt_user_connections_current{user="hello"} 1320
telemt_user_octets_from_client{user="hello"} 34986188595 (32.58 GB)
telemt_user_octets_to_client{user="hello"} 626269197230 (583.26 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 709
telemt_user_unique_ips_recent_window{user="hello"} 390
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 156489.5 (43h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15247925
telemt_connections_bad_total 1413534
telemt_connections_current 2343
telemt_connections_me_current 2343
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 370923
telemt_upstream_connect_attempt_total 70783
telemt_upstream_connect_success_total 70688
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1672
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2611
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 1281
telemt_me_idle_close_by_peer_total 1279
telemt_me_route_drop_no_conn_total 13785490
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12190065
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1164
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
telemt_me_writers_active_current 42
telemt_desync_total 49565
telemt_desync_full_logged_total 15544
telemt_desync_suppressed_total 34021
telemt_desync_frames_bucket_total{bucket="1_2"} 11122
telemt_desync_frames_bucket_total{bucket="3_10"} 19384
telemt_desync_frames_bucket_total{bucket="gt_10"} 19059
telemt_pool_swap_total 168
telemt_pool_force_close_total 5735
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 932
telemt_me_draining_writers_reap_progress_total 51449
telemt_me_writer_removed_unexpected_total 1236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47505
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45714
telemt_me_writer_teardown_success_total{mode="normal"} 51976
telemt_me_writer_teardown_noop_total 51499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103475
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 294.772794
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103475
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 932
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1152
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 12191340
telemt_user_connections_current{user="hello"} 2343
telemt_user_octets_from_client{user="hello"} 171570848073 (159.79 GB)
telemt_user_octets_to_client{user="hello"} 3143340437247 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 362
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 156490.7 (43h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10999339
telemt_connections_bad_total 1064727
telemt_connections_current 1659
telemt_connections_me_current 1659
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 325596
telemt_upstream_connect_attempt_total 82999
telemt_upstream_connect_success_total 81845
telemt_upstream_connect_fail_total 830
telemt_upstream_connect_attempts_per_request{bucket="1"} 82675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 830
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3912
telemt_me_reconnect_success_total 1593
telemt_me_reader_eof_total 1462
telemt_me_idle_close_by_peer_total 1462
telemt_me_route_drop_no_conn_total 4347054
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8206240
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1182
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
telemt_desync_total 36464
telemt_desync_full_logged_total 12253
telemt_desync_suppressed_total 24211
telemt_desync_frames_bucket_total{bucket="1_2"} 8930
telemt_desync_frames_bucket_total{bucket="3_10"} 14055
telemt_desync_frames_bucket_total{bucket="gt_10"} 13479
telemt_pool_swap_total 166
telemt_pool_force_close_total 5158
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 49742
telemt_me_writer_removed_unexpected_total 1492
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4593
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46500
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4682
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44584
telemt_me_writer_teardown_success_total{mode="normal"} 51093
telemt_me_writer_teardown_noop_total 49760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.225607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8145001
telemt_user_connections_current{user="hello"} 1659
telemt_user_octets_from_client{user="hello"} 203965450845 (189.96 GB)
telemt_user_octets_to_client{user="hello"} 3672857596118 (3.34 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 156455.4 (43h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10410096
telemt_connections_bad_total 895415
telemt_connections_current 1377
telemt_connections_me_current 1377
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 332375
telemt_upstream_connect_attempt_total 68191
telemt_upstream_connect_success_total 67258
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2063
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4643
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1626
telemt_me_idle_close_by_peer_total 1625
telemt_me_route_drop_no_conn_total 5117978
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7859708
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1150
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
telemt_me_writers_active_current 42
telemt_desync_total 35984
telemt_desync_full_logged_total 11924
telemt_desync_suppressed_total 24060
telemt_desync_frames_bucket_total{bucket="1_2"} 9114
telemt_desync_frames_bucket_total{bucket="3_10"} 13752
telemt_desync_frames_bucket_total{bucket="gt_10"} 13118
telemt_pool_swap_total 163
telemt_pool_force_close_total 5106
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 50175
telemt_me_writer_removed_unexpected_total 1766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5012
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46841
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 539
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45069
telemt_me_writer_teardown_success_total{mode="normal"} 51853
telemt_me_writer_teardown_noop_total 50246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102099
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.182134
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102099
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1619
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 7852691
telemt_user_connections_current{user="hello"} 1377
telemt_user_octets_from_client{user="hello"} 181239121177 (168.79 GB)
telemt_user_octets_to_client{user="hello"} 3263252053261 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 26734.8 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10071249
telemt_connections_bad_total 615751
telemt_connections_current 2266
telemt_connections_me_current 2266
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 180843
telemt_upstream_connect_attempt_total 35247
telemt_upstream_connect_success_total 33473
telemt_upstream_connect_fail_total 1250
telemt_upstream_connect_attempts_per_request{bucket="1"} 34723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1250
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5869
telemt_me_reconnect_success_total 693
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 24876695
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8387043
telemt_me_endpoint_quarantine_total 168
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 12945
telemt_desync_full_logged_total 3319
telemt_desync_suppressed_total 9626
telemt_desync_frames_bucket_total{bucket="1_2"} 2256
telemt_desync_frames_bucket_total{bucket="3_10"} 5268
telemt_desync_frames_bucket_total{bucket="gt_10"} 5421
telemt_pool_swap_total 25
telemt_pool_force_close_total 1013
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 7246
telemt_me_writer_removed_unexpected_total 596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1224
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6582
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6233
telemt_me_writer_teardown_success_total{mode="normal"} 7806
telemt_me_writer_teardown_noop_total 7251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.573663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 469
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8405254
telemt_user_connections_current{user="hello"} 2266
telemt_user_octets_from_client{user="hello"} 57784574122 (53.82 GB)
telemt_user_octets_to_client{user="hello"} 285008351380 (265.43 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 156461.3 (43h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10185355
telemt_connections_bad_total 850117
telemt_connections_current 1844
telemt_connections_me_current 1844
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 225661
telemt_upstream_connect_attempt_total 96945
telemt_upstream_connect_success_total 95960
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 96798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71739
telemt_me_reconnect_success_total 2594
telemt_me_reader_eof_total 2299
telemt_me_idle_close_by_peer_total 2298
telemt_me_route_drop_no_conn_total 5046136
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8033008
telemt_me_endpoint_quarantine_total 1053
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1166
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 41833
telemt_desync_full_logged_total 14269
telemt_desync_suppressed_total 27564
telemt_desync_frames_bucket_total{bucket="1_2"} 8508
telemt_desync_frames_bucket_total{bucket="3_10"} 16173
telemt_desync_frames_bucket_total{bucket="gt_10"} 17152
telemt_pool_swap_total 159
telemt_pool_force_close_total 4734
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 53268
telemt_me_writer_removed_unexpected_total 2343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49934
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 684
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48534
telemt_me_writer_teardown_success_total{mode="normal"} 55631
telemt_me_writer_teardown_noop_total 53269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108900
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.407215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108900
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 4264
telemt_me_writer_restored_same_endpoint_total 2181
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 8037009
telemt_user_connections_current{user="hello"} 1844
telemt_user_octets_from_client{user="hello"} 181862687789 (169.37 GB)
telemt_user_octets_to_client{user="hello"} 3025921870828 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 93297.5 (25h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10594302
telemt_connections_bad_total 393356
telemt_connections_current 1582
telemt_connections_me_current 1582
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4463905
telemt_upstream_connect_attempt_total 45011
telemt_upstream_connect_success_total 44682
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 45001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_reconnect_attempts_total 48043
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1168
telemt_me_idle_close_by_peer_total 1167
telemt_me_route_drop_no_conn_total 3902372
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5073701
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 701
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 27758
telemt_desync_full_logged_total 9380
telemt_desync_suppressed_total 18378
telemt_desync_frames_bucket_total{bucket="1_2"} 5581
telemt_desync_frames_bucket_total{bucket="3_10"} 10953
telemt_desync_frames_bucket_total{bucket="gt_10"} 11224
telemt_pool_swap_total 98
telemt_pool_force_close_total 3029
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 32061
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2610
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29032
telemt_me_writer_teardown_success_total{mode="normal"} 33322
telemt_me_writer_teardown_noop_total 32068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.762717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1339
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5067311
telemt_user_connections_current{user="hello"} 1582
telemt_user_octets_from_client{user="hello"} 109231318440 (101.73 GB)
telemt_user_octets_to_client{user="hello"} 1912155666510 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 74268.1 (20h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982723
telemt_connections_bad_total 14112
telemt_connections_current 1087
telemt_connections_me_current 1087
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18899
telemt_upstream_connect_attempt_total 36628
telemt_upstream_connect_success_total 36536
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 36612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1643
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 337021
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870938
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 615
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4848
telemt_desync_full_logged_total 1485
telemt_desync_suppressed_total 3363
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 1936
telemt_desync_frames_bucket_total{bucket="gt_10"} 1775
telemt_pool_swap_total 79
telemt_pool_force_close_total 1996
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 30317
telemt_me_writer_removed_unexpected_total 647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2337
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28652
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28321
telemt_me_writer_teardown_success_total{mode="normal"} 30989
telemt_me_writer_teardown_noop_total 30320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.538350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 871952
telemt_user_connections_current{user="hello"} 1087
telemt_user_octets_from_client{user="hello"} 15750704657 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 389433720815 (362.69 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 156466.0 (43h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12456765
telemt_connections_bad_total 1444056
telemt_connections_current 2146
telemt_connections_me_current 2146
telemt_handshake_timeouts_total 342811
telemt_upstream_connect_attempt_total 58716
telemt_upstream_connect_success_total 58489
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 58666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2275
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 4154509
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9416698
telemt_me_endpoint_quarantine_total 1055
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1168
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
telemt_me_writers_active_current 47
telemt_desync_total 38613
telemt_desync_full_logged_total 12604
telemt_desync_suppressed_total 26009
telemt_desync_frames_bucket_total{bucket="1_2"} 9192
telemt_desync_frames_bucket_total{bucket="3_10"} 14300
telemt_desync_frames_bucket_total{bucket="gt_10"} 15121
telemt_pool_swap_total 173
telemt_pool_force_close_total 4780
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 617
telemt_me_draining_writers_reap_progress_total 52884
telemt_me_writer_removed_unexpected_total 1136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49724
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48104
telemt_me_writer_teardown_success_total{mode="normal"} 54053
telemt_me_writer_teardown_noop_total 52886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106939
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.002305
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106939
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 617
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1067
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9386024
telemt_user_connections_current{user="hello"} 2146
telemt_user_octets_from_client{user="hello"} 183734147960 (171.12 GB)
telemt_user_octets_to_client{user="hello"} 4147165356596 (3.77 TB)
telemt_user_unique_ips_current{user="hello"} 748
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 156462.5 (43h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10800447
telemt_connections_bad_total 1207921
telemt_connections_current 1486
telemt_connections_me_current 1486
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 278564
telemt_upstream_connect_attempt_total 84448
telemt_upstream_connect_success_total 83816
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 84363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_reconnect_attempts_total 8877
telemt_me_reconnect_success_total 2040
telemt_me_reader_eof_total 1905
telemt_me_idle_close_by_peer_total 1905
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5403064
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8347685
telemt_me_endpoint_quarantine_total 1183
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1170
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
telemt_me_writers_active_current 45
telemt_desync_total 38137
telemt_desync_full_logged_total 12319
telemt_desync_suppressed_total 25818
telemt_desync_frames_bucket_total{bucket="1_2"} 9473
telemt_desync_frames_bucket_total{bucket="3_10"} 14214
telemt_desync_frames_bucket_total{bucket="gt_10"} 14450
telemt_pool_swap_total 165
telemt_pool_force_close_total 4628
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 52297
telemt_me_writer_removed_unexpected_total 1931
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5422
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4189
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47669
telemt_me_writer_teardown_success_total{mode="normal"} 54296
telemt_me_writer_teardown_noop_total 52302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106598
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.478996
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106598
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8353703
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 147068256725 (136.97 GB)
telemt_user_octets_to_client{user="hello"} 3187674050759 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 206
```