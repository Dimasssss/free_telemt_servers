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

# Server Metrics 2026-03-23 02:12:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 104737.0 (29h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3601807
telemt_connections_bad_total 333289
telemt_connections_current 971
telemt_connections_me_current 971
telemt_handshake_timeouts_total 113762
telemt_upstream_connect_attempt_total 39067
telemt_upstream_connect_success_total 39066
telemt_upstream_connect_attempts_per_request{bucket="1"} 39066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1411
telemt_me_reconnect_success_total 614
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 631
telemt_me_route_drop_no_conn_total 2995717
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2958481
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 818
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
telemt_desync_total 12764
telemt_desync_full_logged_total 4026
telemt_desync_suppressed_total 8738
telemt_desync_frames_bucket_total{bucket="1_2"} 3402
telemt_desync_frames_bucket_total{bucket="3_10"} 4654
telemt_desync_frames_bucket_total{bucket="gt_10"} 4708
telemt_pool_swap_total 116
telemt_pool_force_close_total 3560
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 35783
telemt_me_writer_removed_unexpected_total 608
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2550
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33490
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3504
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32223
telemt_me_writer_teardown_success_total{mode="normal"} 36040
telemt_me_writer_teardown_noop_total 35794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.806407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 550
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2947462
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 42191438060 (39.29 GB)
telemt_user_octets_to_client{user="hello"} 806804113488 (751.39 GB)
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 118102.9 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4018984
telemt_connections_bad_total 371725
telemt_connections_current 396
telemt_connections_me_current 396
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101038
telemt_upstream_connect_attempt_total 73560
telemt_upstream_connect_success_total 72658
telemt_upstream_connect_fail_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 73453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 795
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10287
telemt_me_reconnect_success_total 3681
telemt_me_reader_eof_total 3667
telemt_me_idle_close_by_peer_total 3667
telemt_me_route_drop_no_conn_total 3643279
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3192486
telemt_me_endpoint_quarantine_total 956
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 47
telemt_me_single_endpoint_outage_exit_total 47
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 926
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
telemt_me_writers_active_current 42
telemt_desync_total 13022
telemt_desync_full_logged_total 7312
telemt_desync_suppressed_total 5710
telemt_desync_frames_bucket_total{bucket="1_2"} 2956
telemt_desync_frames_bucket_total{bucket="3_10"} 5112
telemt_desync_frames_bucket_total{bucket="gt_10"} 4954
telemt_pool_swap_total 111
telemt_pool_force_close_total 3119
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 48822
telemt_me_writer_removed_unexpected_total 3596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6367
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46085
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45703
telemt_me_writer_teardown_success_total{mode="normal"} 52452
telemt_me_writer_teardown_noop_total 48823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101275
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.643448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101275
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 3271
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 3205853
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 43240685826 (40.27 GB)
telemt_user_octets_to_client{user="hello"} 795325584054 (740.70 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 192962.8 (53h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16385206
telemt_connections_bad_total 1659835
telemt_connections_current 941
telemt_connections_me_current 941
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398265
telemt_upstream_connect_attempt_total 86720
telemt_upstream_connect_success_total 86614
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 86631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3033
telemt_me_reconnect_success_total 1609
telemt_me_reader_eof_total 1556
telemt_me_idle_close_by_peer_total 1554
telemt_me_route_drop_no_conn_total 14052169
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13009870
telemt_me_endpoint_quarantine_total 1289
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1455
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
telemt_me_writers_active_current 46
telemt_desync_total 53968
telemt_desync_full_logged_total 17164
telemt_desync_suppressed_total 36804
telemt_desync_frames_bucket_total{bucket="1_2"} 12036
telemt_desync_frames_bucket_total{bucket="3_10"} 21078
telemt_desync_frames_bucket_total{bucket="gt_10"} 20854
telemt_pool_swap_total 209
telemt_pool_force_close_total 6811
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1066
telemt_me_draining_writers_reap_progress_total 65967
telemt_me_writer_removed_unexpected_total 1497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61152
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6341
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59156
telemt_me_writer_teardown_success_total{mode="normal"} 66742
telemt_me_writer_teardown_noop_total 66020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132762
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.885352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132762
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1066
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1392
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13009866
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 197350319205 (183.80 GB)
telemt_user_octets_to_client{user="hello"} 3501507411731 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 192964.1 (53h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11926694
telemt_connections_bad_total 1245081
telemt_connections_current 625
telemt_connections_me_current 625
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344823
telemt_upstream_connect_attempt_total 101093
telemt_upstream_connect_success_total 99763
telemt_upstream_connect_fail_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 100640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 877
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4468
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1785
telemt_me_route_drop_no_conn_total 4561493
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8847310
telemt_me_endpoint_quarantine_total 1304
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1475
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
telemt_me_writers_active_current 46
telemt_desync_total 39006
telemt_desync_full_logged_total 13136
telemt_desync_suppressed_total 25870
telemt_desync_frames_bucket_total{bucket="1_2"} 9665
telemt_desync_frames_bucket_total{bucket="3_10"} 14979
telemt_desync_frames_bucket_total{bucket="gt_10"} 14362
telemt_pool_swap_total 206
telemt_pool_force_close_total 6164
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 64184
telemt_me_writer_removed_unexpected_total 1812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60153
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58020
telemt_me_writer_teardown_success_total{mode="normal"} 65855
telemt_me_writer_teardown_noop_total 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130064
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.519332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130064
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1642
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8785047
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 218065160496 (203.09 GB)
telemt_user_octets_to_client{user="hello"} 3971916896435 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 192928.1 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11089835
telemt_connections_bad_total 982553
telemt_connections_current 498
telemt_connections_me_current 498
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345708
telemt_upstream_connect_attempt_total 85368
telemt_upstream_connect_success_total 83808
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 84013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5773
telemt_me_reconnect_success_total 2394
telemt_me_reader_eof_total 2138
telemt_me_idle_close_by_peer_total 2137
telemt_me_route_drop_no_conn_total 5341900
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8379660
telemt_me_endpoint_quarantine_total 1361
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1433
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38238
telemt_desync_full_logged_total 12667
telemt_desync_suppressed_total 25571
telemt_desync_frames_bucket_total{bucket="1_2"} 9659
telemt_desync_frames_bucket_total{bucket="3_10"} 14636
telemt_desync_frames_bucket_total{bucket="gt_10"} 13943
telemt_pool_swap_total 202
telemt_pool_force_close_total 6060
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 64599
telemt_me_writer_removed_unexpected_total 2288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6437
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58539
telemt_me_writer_teardown_success_total{mode="normal"} 66819
telemt_me_writer_teardown_noop_total 64670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.843614
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2083
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8371599
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 192888089111 (179.64 GB)
telemt_user_octets_to_client{user="hello"} 3477469803945 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63208.6 (17h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11308256
telemt_connections_bad_total 669748
telemt_connections_current 936
telemt_connections_me_current 936
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 281174
telemt_upstream_connect_attempt_total 59775
telemt_upstream_connect_success_total 56661
telemt_upstream_connect_fail_total 2041
telemt_upstream_connect_attempts_per_request{bucket="1"} 58702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2041
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7810
telemt_me_reconnect_success_total 1279
telemt_me_reader_eof_total 808
telemt_me_idle_close_by_peer_total 807
telemt_me_route_drop_no_conn_total 25298891
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9378314
telemt_me_endpoint_quarantine_total 474
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_desync_total 16452
telemt_desync_full_logged_total 4505
telemt_desync_suppressed_total 11947
telemt_desync_frames_bucket_total{bucket="1_2"} 3128
telemt_desync_frames_bucket_total{bucket="3_10"} 6707
telemt_desync_frames_bucket_total{bucket="gt_10"} 6617
telemt_pool_swap_total 66
telemt_pool_force_close_total 2110
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 20227
telemt_me_writer_removed_unexpected_total 1164
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18117
telemt_me_writer_teardown_success_total{mode="normal"} 21335
telemt_me_writer_teardown_noop_total 20246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.963443
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9404160
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 87630948498 (81.61 GB)
telemt_user_octets_to_client{user="hello"} 622545199698 (579.79 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 192934.7 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11045114
telemt_connections_bad_total 964832
telemt_connections_current 617
telemt_connections_me_current 617
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243208
telemt_upstream_connect_attempt_total 114205
telemt_upstream_connect_success_total 113030
telemt_upstream_connect_fail_total 1001
telemt_upstream_connect_attempts_per_request{bucket="1"} 114031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1001
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73056
telemt_me_reconnect_success_total 3128
telemt_me_reader_eof_total 2819
telemt_me_idle_close_by_peer_total 2817
telemt_me_route_drop_no_conn_total 5268808
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8704948
telemt_me_endpoint_quarantine_total 1307
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1461
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
telemt_me_writers_active_current 45
telemt_desync_total 46369
telemt_desync_full_logged_total 15904
telemt_desync_suppressed_total 30465
telemt_desync_frames_bucket_total{bucket="1_2"} 9429
telemt_desync_frames_bucket_total{bucket="3_10"} 17745
telemt_desync_frames_bucket_total{bucket="gt_10"} 19195
telemt_pool_swap_total 198
telemt_pool_force_close_total 5772
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 68643
telemt_me_writer_removed_unexpected_total 2843
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6977
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64549
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5023
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62871
telemt_me_writer_teardown_success_total{mode="normal"} 71526
telemt_me_writer_teardown_noop_total 68644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.289857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 4304
telemt_me_writer_restored_same_endpoint_total 2635
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 8707884
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 194977624817 (181.59 GB)
telemt_user_octets_to_client{user="hello"} 3328501011872 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 129771.0 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11746216
telemt_connections_bad_total 482870
telemt_connections_current 670
telemt_connections_me_current 670
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4766992
telemt_upstream_connect_attempt_total 62756
telemt_upstream_connect_success_total 62296
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 62744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 49097
telemt_me_reconnect_success_total 1864
telemt_me_reader_eof_total 1541
telemt_me_idle_close_by_peer_total 1540
telemt_me_route_drop_no_conn_total 4098344
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5645275
telemt_me_endpoint_quarantine_total 887
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 997
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31772
telemt_desync_full_logged_total 10849
telemt_desync_suppressed_total 20923
telemt_desync_frames_bucket_total{bucket="1_2"} 6332
telemt_desync_frames_bucket_total{bucket="3_10"} 12537
telemt_desync_frames_bucket_total{bucket="gt_10"} 12903
telemt_pool_swap_total 138
telemt_pool_force_close_total 3967
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 48096
telemt_me_writer_removed_unexpected_total 1586
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3907
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44129
telemt_me_writer_teardown_success_total{mode="normal"} 49731
telemt_me_writer_teardown_noop_total 48103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.714847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1648
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5637410
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 120109788492 (111.86 GB)
telemt_user_octets_to_client{user="hello"} 2188893869526 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 110742.0 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1547359
telemt_connections_bad_total 36829
telemt_connections_current 473
telemt_connections_me_current 473
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31662
telemt_upstream_connect_attempt_total 52396
telemt_upstream_connect_success_total 52235
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 52368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 796
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2295
telemt_me_reconnect_success_total 942
telemt_me_reader_eof_total 930
telemt_me_idle_close_by_peer_total 930
telemt_me_route_drop_no_conn_total 522412
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1375721
telemt_me_endpoint_quarantine_total 930
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 915
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 13
telemt_desync_total 9412
telemt_desync_full_logged_total 2707
telemt_desync_suppressed_total 6705
telemt_desync_frames_bucket_total{bucket="1_2"} 2777
telemt_desync_frames_bucket_total{bucket="3_10"} 3578
telemt_desync_frames_bucket_total{bucket="gt_10"} 3057
telemt_pool_swap_total 119
telemt_pool_force_close_total 3019
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 44419
telemt_me_writer_removed_unexpected_total 896
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3380
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41400
telemt_me_writer_teardown_success_total{mode="normal"} 45356
telemt_me_writer_teardown_noop_total 44423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.381897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1371518
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 26217982509 (24.42 GB)
telemt_user_octets_to_client{user="hello"} 582498614503 (542.49 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 192939.4 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13369214
telemt_connections_bad_total 1615728
telemt_connections_current 649
telemt_connections_me_current 649
telemt_handshake_timeouts_total 390292
telemt_upstream_connect_attempt_total 76698
telemt_upstream_connect_success_total 76344
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 76562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3043
telemt_me_reconnect_success_total 1523
telemt_me_reader_eof_total 1506
telemt_me_idle_close_by_peer_total 1506
telemt_me_route_drop_no_conn_total 4487078
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10070982
telemt_me_endpoint_quarantine_total 1399
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1462
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
telemt_me_writers_active_current 45
telemt_desync_total 42225
telemt_desync_full_logged_total 13787
telemt_desync_suppressed_total 28438
telemt_desync_frames_bucket_total{bucket="1_2"} 10253
telemt_desync_frames_bucket_total{bucket="3_10"} 15509
telemt_desync_frames_bucket_total{bucket="gt_10"} 16463
telemt_pool_swap_total 214
telemt_pool_force_close_total 5656
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 69373
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65449
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5482
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63717
telemt_me_writer_teardown_success_total{mode="normal"} 70869
telemt_me_writer_teardown_noop_total 69375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.822035
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1336
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10037669
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 194952892388 (181.56 GB)
telemt_user_octets_to_client{user="hello"} 4449566745036 (4.05 TB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 192935.8 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11678210
telemt_connections_bad_total 1364606
telemt_connections_current 507
telemt_connections_me_current 507
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312392
telemt_upstream_connect_attempt_total 104264
telemt_upstream_connect_success_total 103360
telemt_upstream_connect_fail_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 104056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 696
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10669
telemt_me_reconnect_success_total 2632
telemt_me_reader_eof_total 2443
telemt_me_idle_close_by_peer_total 2442
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5654605
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8985748
telemt_me_endpoint_quarantine_total 1582
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1465
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41917
telemt_desync_full_logged_total 13499
telemt_desync_suppressed_total 28418
telemt_desync_frames_bucket_total{bucket="1_2"} 10838
telemt_desync_frames_bucket_total{bucket="3_10"} 15415
telemt_desync_frames_bucket_total{bucket="gt_10"} 15664
telemt_pool_swap_total 204
telemt_pool_force_close_total 5429
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 69476
telemt_me_writer_removed_unexpected_total 2484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6809
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64047
telemt_me_writer_teardown_success_total{mode="normal"} 72050
telemt_me_writer_teardown_noop_total 69481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141531
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.501509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141531
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2113
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 8990318
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 157557436024 (146.74 GB)
telemt_user_octets_to_client{user="hello"} 3500708658606 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 58
```