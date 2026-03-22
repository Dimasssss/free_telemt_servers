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

# Server Metrics 2026-03-22 08:08:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 39705.7 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 910593
telemt_connections_bad_total 53846
telemt_connections_current 1716
telemt_connections_me_current 1716
telemt_handshake_timeouts_total 42137
telemt_upstream_connect_attempt_total 15906
telemt_upstream_connect_success_total 15905
telemt_upstream_connect_attempts_per_request{bucket="1"} 15905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 436
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 525570
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758440
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_shadow_rotate_total 321
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
telemt_me_writers_warm_current 40
telemt_desync_total 5728
telemt_desync_full_logged_total 1611
telemt_desync_suppressed_total 4117
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 2154
telemt_desync_frames_bucket_total{bucket="gt_10"} 1791
telemt_pool_swap_total 43
telemt_pool_force_close_total 1205
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 14396
telemt_me_writer_removed_unexpected_total 242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13598
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13191
telemt_me_writer_teardown_success_total{mode="normal"} 14591
telemt_me_writer_teardown_noop_total 14397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28988
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.388760
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28988
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 757041
telemt_user_connections_current{user="hello"} 1716
telemt_user_octets_from_client{user="hello"} 10320390968 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 243914706276 (227.16 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 53072.4 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1380226
telemt_connections_bad_total 134724
telemt_connections_current 2450
telemt_connections_me_current 2450
telemt_handshake_timeouts_total 41171
telemt_upstream_connect_attempt_total 27707
telemt_upstream_connect_success_total 27295
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 27655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 567836
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041504
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 423
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
telemt_me_writers_active_current 87
telemt_desync_total 4559
telemt_desync_full_logged_total 2663
telemt_desync_suppressed_total 1896
telemt_desync_frames_bucket_total{bucket="1_2"} 993
telemt_desync_frames_bucket_total{bucket="3_10"} 1763
telemt_desync_frames_bucket_total{bucket="gt_10"} 1803
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 21666
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20426
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20186
telemt_me_writer_teardown_success_total{mode="normal"} 22387
telemt_me_writer_teardown_noop_total 21666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.921877
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 675
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1043157
telemt_user_connections_current{user="hello"} 2450
telemt_user_octets_from_client{user="hello"} 16239115890 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 368786675575 (343.46 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 127932.1 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9423949
telemt_connections_bad_total 852707
telemt_connections_current 5258
telemt_connections_me_current 5258
telemt_handshake_timeouts_total 287536
telemt_upstream_connect_attempt_total 47102
telemt_upstream_connect_success_total 47021
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1854
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 951
telemt_me_idle_close_by_peer_total 951
telemt_me_route_drop_no_conn_total 5153962
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7397422
telemt_me_endpoint_quarantine_total 802
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 958
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 55
telemt_me_writers_warm_current 29
telemt_desync_total 32174
telemt_desync_full_logged_total 10613
telemt_desync_suppressed_total 21561
telemt_desync_frames_bucket_total{bucket="1_2"} 7044
telemt_desync_frames_bucket_total{bucket="3_10"} 12460
telemt_desync_frames_bucket_total{bucket="gt_10"} 12670
telemt_pool_swap_total 138
telemt_pool_force_close_total 4564
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 42958
telemt_me_writer_removed_unexpected_total 915
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4287
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38394
telemt_me_writer_teardown_success_total{mode="normal"} 43351
telemt_me_writer_teardown_noop_total 43002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86353
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 182.201428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86353
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 844
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 7387841
telemt_user_connections_current{user="hello"} 5258
telemt_user_octets_from_client{user="hello"} 123395059388 (114.92 GB)
telemt_user_octets_to_client{user="hello"} 2496796427400 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 1991
telemt_user_unique_ips_recent_window{user="hello"} 804
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 127933.3 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7736626
telemt_connections_bad_total 686596
telemt_connections_current 3965
telemt_connections_me_current 3965
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 251171
telemt_upstream_connect_attempt_total 53334
telemt_upstream_connect_success_total 52860
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 53102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25843
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2809
telemt_me_reconnect_success_total 1058
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 980
telemt_me_route_drop_no_conn_total 2593996
telemt_me_route_drop_channel_closed_total 312
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5726310
telemt_me_endpoint_quarantine_total 812
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 987
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
telemt_desync_total 26271
telemt_desync_full_logged_total 8986
telemt_desync_suppressed_total 17285
telemt_desync_frames_bucket_total{bucket="1_2"} 6296
telemt_desync_frames_bucket_total{bucket="3_10"} 10181
telemt_desync_frames_bucket_total{bucket="gt_10"} 9794
telemt_pool_swap_total 140
telemt_pool_force_close_total 4140
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 41385
telemt_me_writer_removed_unexpected_total 1002
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37245
telemt_me_writer_teardown_success_total{mode="normal"} 42309
telemt_me_writer_teardown_noop_total 41391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83700
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.684571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83700
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5649172
telemt_user_connections_current{user="hello"} 3965
telemt_user_octets_from_client{user="hello"} 157788726443 (146.95 GB)
telemt_user_octets_to_client{user="hello"} 2713439030710 (2.47 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1624
telemt_user_unique_ips_recent_window{user="hello"} 634
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 127897.3 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7462761
telemt_connections_bad_total 616495
telemt_connections_current 4101
telemt_connections_me_current 4101
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246907
telemt_upstream_connect_attempt_total 57726
telemt_upstream_connect_success_total 57056
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2741
telemt_me_reconnect_success_total 1193
telemt_me_reader_eof_total 1100
telemt_me_idle_close_by_peer_total 1100
telemt_me_route_drop_no_conn_total 3006871
telemt_me_route_drop_channel_closed_total 176
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5565376
telemt_me_endpoint_quarantine_total 897
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 942
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 29
telemt_desync_total 26010
telemt_desync_full_logged_total 8878
telemt_desync_suppressed_total 17132
telemt_desync_frames_bucket_total{bucket="1_2"} 6286
telemt_desync_frames_bucket_total{bucket="3_10"} 9996
telemt_desync_frames_bucket_total{bucket="gt_10"} 9728
telemt_pool_swap_total 136
telemt_pool_force_close_total 4045
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 459
telemt_me_draining_writers_reap_progress_total 42403
telemt_me_writer_removed_unexpected_total 1111
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3746
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39751
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38358
telemt_me_writer_teardown_success_total{mode="normal"} 43497
telemt_me_writer_teardown_noop_total 42415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.376073
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 459
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1034
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5558574
telemt_user_connections_current{user="hello"} 4101
telemt_user_octets_from_client{user="hello"} 145764443815 (135.75 GB)
telemt_user_octets_to_client{user="hello"} 2474984414707 (2.25 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1657
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 127936.5 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23960665
telemt_connections_bad_total 1968944
telemt_connections_current 6008
telemt_connections_me_current 6008
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 693695
telemt_upstream_connect_attempt_total 241356
telemt_upstream_connect_success_total 221601
telemt_upstream_connect_fail_total 17759
telemt_upstream_connect_attempts_per_request{bucket="1"} 239360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17759
telemt_me_keepalive_timeout_total 448
telemt_me_reconnect_attempts_total 66519
telemt_me_reconnect_success_total 2697
telemt_me_reader_eof_total 1677
telemt_me_idle_close_by_peer_total 1675
telemt_me_route_drop_no_conn_total 46338289
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19365004
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 1004
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
telemt_me_writers_active_current 44
telemt_desync_total 37530
telemt_desync_full_logged_total 11104
telemt_desync_suppressed_total 26426
telemt_desync_frames_bucket_total{bucket="1_2"} 8334
telemt_desync_frames_bucket_total{bucket="3_10"} 16593
telemt_desync_frames_bucket_total{bucket="gt_10"} 12603
telemt_pool_swap_total 133
telemt_pool_force_close_total 4190
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 967
telemt_me_draining_writers_reap_progress_total 39842
telemt_me_writer_removed_unexpected_total 2500
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5391
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 595
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35652
telemt_me_writer_teardown_success_total{mode="normal"} 42066
telemt_me_writer_teardown_noop_total 39874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.288851
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 967
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1825
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 19530465
telemt_user_connections_current{user="hello"} 6009
telemt_user_octets_from_client{user="hello"} 277102650423 (258.07 GB)
telemt_user_octets_to_client{user="hello"} 1433448393147 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2038
telemt_user_unique_ips_recent_window{user="hello"} 1623
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 127903.8 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7093141
telemt_connections_bad_total 643729
telemt_connections_current 4269
telemt_connections_me_current 4269
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 145997
telemt_upstream_connect_attempt_total 66170
telemt_upstream_connect_success_total 65396
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 66064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_reconnect_attempts_total 70200
telemt_me_reconnect_success_total 1962
telemt_me_reader_eof_total 1729
telemt_me_idle_close_by_peer_total 1728
telemt_me_route_drop_no_conn_total 2733644
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5566554
telemt_me_endpoint_quarantine_total 853
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 969
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 25
telemt_desync_total 28052
telemt_desync_full_logged_total 9773
telemt_desync_suppressed_total 18279
telemt_desync_frames_bucket_total{bucket="1_2"} 5602
telemt_desync_frames_bucket_total{bucket="3_10"} 10795
telemt_desync_frames_bucket_total{bucket="gt_10"} 11655
telemt_pool_swap_total 133
telemt_pool_force_close_total 3832
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 44565
telemt_me_writer_removed_unexpected_total 1760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41887
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 426
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40733
telemt_me_writer_teardown_success_total{mode="normal"} 46350
telemt_me_writer_teardown_noop_total 44566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.158497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 4224
telemt_me_writer_restored_same_endpoint_total 1634
telemt_me_writer_restored_fallback_total 39
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5557464
telemt_user_connections_current{user="hello"} 4269
telemt_user_octets_from_client{user="hello"} 140368235540 (130.73 GB)
telemt_user_octets_to_client{user="hello"} 2317570140962 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1623
telemt_user_unique_ips_recent_window{user="hello"} 683
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 64739.8 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5454459
telemt_connections_bad_total 216320
telemt_connections_current 4392
telemt_connections_me_current 4392
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2166159
telemt_upstream_connect_attempt_total 35217
telemt_upstream_connect_success_total 34971
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 35210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_reconnect_attempts_total 46364
telemt_me_reconnect_success_total 1136
telemt_me_reader_eof_total 828
telemt_me_idle_close_by_peer_total 828
telemt_me_route_drop_no_conn_total 1351173
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2727265
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 87
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14683
telemt_desync_full_logged_total 5029
telemt_desync_suppressed_total 9654
telemt_desync_frames_bucket_total{bucket="1_2"} 2861
telemt_desync_frames_bucket_total{bucket="3_10"} 5648
telemt_desync_frames_bucket_total{bucket="gt_10"} 6174
telemt_pool_swap_total 69
telemt_pool_force_close_total 2031
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 188
telemt_me_draining_writers_reap_progress_total 23412
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1997
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21381
telemt_me_writer_teardown_success_total{mode="normal"} 24332
telemt_me_writer_teardown_noop_total 23414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47746
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.284856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47746
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 188
telemt_me_refill_failed_total 2627
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2728775
telemt_user_connections_current{user="hello"} 4392
telemt_user_octets_from_client{user="hello"} 69753684292 (64.96 GB)
telemt_user_octets_to_client{user="hello"} 1206326978962 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1846
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45710.9 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380045
telemt_connections_bad_total 2605
telemt_connections_current 1013
telemt_connections_me_current 1013
telemt_handshake_timeouts_total 8005
telemt_upstream_connect_attempt_total 21623
telemt_upstream_connect_success_total 21569
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 929
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 314
telemt_me_idle_close_by_peer_total 314
telemt_me_route_drop_no_conn_total 118194
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345623
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
telemt_me_writers_active_current 44
telemt_desync_total 1593
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1133
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 619
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 50
telemt_pool_force_close_total 1141
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 19534
telemt_me_writer_removed_unexpected_total 300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1296
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18552
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18393
telemt_me_writer_teardown_success_total{mode="normal"} 19848
telemt_me_writer_teardown_noop_total 19534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.809435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 269
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 345040
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 6383740412 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 184318490216 (171.66 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 127908.4 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8710417
telemt_connections_bad_total 974390
telemt_connections_current 4951
telemt_connections_me_current 4951
telemt_handshake_timeouts_total 243656
telemt_upstream_connect_attempt_total 49894
telemt_upstream_connect_success_total 49710
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 49855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25063
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 1838
telemt_me_reconnect_success_total 1000
telemt_me_reader_eof_total 978
telemt_me_idle_close_by_peer_total 978
telemt_me_route_drop_no_conn_total 2435784
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6460885
telemt_me_endpoint_quarantine_total 900
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 971
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
telemt_me_writers_warm_current 39
telemt_desync_total 25886
telemt_desync_full_logged_total 8517
telemt_desync_suppressed_total 17369
telemt_desync_frames_bucket_total{bucket="1_2"} 6393
telemt_desync_frames_bucket_total{bucket="3_10"} 9409
telemt_desync_frames_bucket_total{bucket="gt_10"} 10084
telemt_pool_swap_total 141
telemt_pool_force_close_total 3779
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 451
telemt_me_draining_writers_reap_progress_total 45003
telemt_me_writer_removed_unexpected_total 939
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42410
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41224
telemt_me_writer_teardown_success_total{mode="normal"} 45971
telemt_me_writer_teardown_noop_total 45005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90976
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.560304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90976
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 451
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6434268
telemt_user_connections_current{user="hello"} 4951
telemt_user_octets_from_client{user="hello"} 126305982348 (117.63 GB)
telemt_user_octets_to_client{user="hello"} 3022900226956 (2.75 TB)
telemt_user_unique_ips_current{user="hello"} 1877
telemt_user_unique_ips_recent_window{user="hello"} 676
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 127905.0 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7598635
telemt_connections_bad_total 832565
telemt_connections_current 4502
telemt_connections_me_current 4502
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 203482
telemt_upstream_connect_attempt_total 65954
telemt_upstream_connect_success_total 65448
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 65891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 6159
telemt_me_reconnect_success_total 1413
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1274
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2553642
telemt_me_route_drop_channel_closed_total 211
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5781027
telemt_me_endpoint_quarantine_total 997
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 970
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 31
telemt_desync_total 24792
telemt_desync_full_logged_total 8234
telemt_desync_suppressed_total 16558
telemt_desync_frames_bucket_total{bucket="1_2"} 6120
telemt_desync_frames_bucket_total{bucket="3_10"} 9124
telemt_desync_frames_bucket_total{bucket="gt_10"} 9548
telemt_pool_swap_total 138
telemt_pool_force_close_total 3722
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 43689
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40883
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39967
telemt_me_writer_teardown_success_total{mode="normal"} 45039
telemt_me_writer_teardown_noop_total 43693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88732
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.709449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88732
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 1108
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5782298
telemt_user_connections_current{user="hello"} 4502
telemt_user_octets_from_client{user="hello"} 106253546525 (98.96 GB)
telemt_user_octets_to_client{user="hello"} 2508872547500 (2.28 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1789
telemt_user_unique_ips_recent_window{user="hello"} 617
```