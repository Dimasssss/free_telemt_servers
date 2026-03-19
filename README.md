# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
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

## rdp-onedash.ru
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

## 4vps.su
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

# Server Metrics 2026-03-19 21:03:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 13568.5 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354441
telemt_connections_bad_total 17191
telemt_connections_current 940
telemt_connections_me_current 940
telemt_handshake_timeouts_total 5337
telemt_upstream_connect_attempt_total 2149
telemt_upstream_connect_success_total 2127
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1432
telemt_me_reconnect_success_total 1422
telemt_me_reader_eof_total 1494
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 108268
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280154
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1428
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 934
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1455
telemt_me_writer_restored_same_endpoint_total 1409
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 280406
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 10752562644 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 102765370312 (95.71 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 30023.5 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2617861
telemt_connections_bad_total 110641
telemt_connections_current 2587
telemt_connections_me_current 2587
telemt_handshake_timeouts_total 50744
telemt_upstream_connect_attempt_total 6189
telemt_upstream_connect_success_total 6093
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 6189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7563
telemt_me_reconnect_success_total 3335
telemt_me_reader_eof_total 3595
telemt_me_idle_close_by_peer_total 3595
telemt_me_route_drop_no_conn_total 1386801
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2229331
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9802
telemt_desync_full_logged_total 3207
telemt_desync_suppressed_total 6595
telemt_desync_frames_bucket_total{bucket="1_2"} 1817
telemt_desync_frames_bucket_total{bucket="3_10"} 3833
telemt_desync_frames_bucket_total{bucket="gt_10"} 4152
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3500
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3280
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2229278
telemt_user_connections_current{user="hello"} 2587
telemt_user_octets_from_client{user="hello"} 34338603902 (31.98 GB)
telemt_user_octets_to_client{user="hello"} 788406184862 (734.26 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 30002.0 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2539493
telemt_connections_bad_total 430517
telemt_connections_current 1936
telemt_connections_me_current 1936
telemt_handshake_timeouts_total 29758
telemt_upstream_connect_attempt_total 4677
telemt_upstream_connect_success_total 4642
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4034
telemt_me_reconnect_success_total 3109
telemt_me_reader_eof_total 3221
telemt_me_idle_close_by_peer_total 3220
telemt_me_route_drop_no_conn_total 1826503
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1797053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6782
telemt_desync_full_logged_total 2030
telemt_desync_suppressed_total 4752
telemt_desync_frames_bucket_total{bucket="1_2"} 1723
telemt_desync_frames_bucket_total{bucket="3_10"} 2553
telemt_desync_frames_bucket_total{bucket="gt_10"} 2506
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3122
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3108
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 1792995
telemt_user_connections_current{user="hello"} 1936
telemt_user_octets_from_client{user="hello"} 25778374528 (24.01 GB)
telemt_user_octets_to_client{user="hello"} 637761307740 (593.96 GB)
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 29989.4 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2238694
telemt_connections_bad_total 91142
telemt_connections_current 1953
telemt_connections_me_current 1953
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27807
telemt_upstream_connect_attempt_total 31945
telemt_upstream_connect_success_total 30385
telemt_upstream_connect_fail_total 1560
telemt_upstream_connect_attempts_per_request{bucket="1"} 31945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1560
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6103
telemt_me_reconnect_success_total 3556
telemt_me_reader_eof_total 3699
telemt_me_idle_close_by_peer_total 3698
telemt_me_route_drop_no_conn_total 1788356
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1911001
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7674
telemt_desync_full_logged_total 2390
telemt_desync_suppressed_total 5284
telemt_desync_frames_bucket_total{bucket="1_2"} 1900
telemt_desync_frames_bucket_total{bucket="3_10"} 2783
telemt_desync_frames_bucket_total{bucket="gt_10"} 2991
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 292
telemt_me_writer_removed_unexpected_total 4024
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3552
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 1935171
telemt_user_connections_current{user="hello"} 1953
telemt_user_octets_from_client{user="hello"} 32262389480 (30.05 GB)
telemt_user_octets_to_client{user="hello"} 475286404746 (442.64 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 83712.7 (23h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5912977
telemt_connections_bad_total 1029802
telemt_connections_current 2325
telemt_connections_me_current 2325
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107620
telemt_upstream_connect_attempt_total 66195
telemt_upstream_connect_success_total 63694
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75767
telemt_me_reconnect_success_total 10351
telemt_me_reader_eof_total 10926
telemt_me_idle_close_by_peer_total 10923
telemt_me_route_drop_no_conn_total 2705006
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4179541
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18328
telemt_desync_full_logged_total 5691
telemt_desync_suppressed_total 12637
telemt_desync_frames_bucket_total{bucket="1_2"} 3137
telemt_desync_frames_bucket_total{bucket="3_10"} 7602
telemt_desync_frames_bucket_total{bucket="gt_10"} 7589
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 10611
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10327
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 4227595
telemt_user_connections_current{user="hello"} 2325
telemt_user_octets_from_client{user="hello"} 65845573351 (61.32 GB)
telemt_user_octets_to_client{user="hello"} 1619643423888 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 29952.8 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600976
telemt_connections_bad_total 46646
telemt_connections_current 521
telemt_connections_me_current 521
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11572
telemt_upstream_connect_attempt_total 8633
telemt_upstream_connect_success_total 8436
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3975
telemt_me_reconnect_success_total 3912
telemt_me_reader_eof_total 4067
telemt_me_idle_close_by_peer_total 4066
telemt_me_route_drop_no_conn_total 394561
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478847
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1283
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 139
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3947
telemt_me_writer_restored_same_endpoint_total 3903
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 497467
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 6210150856 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 108643600214 (101.18 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 29954.2 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1765373
telemt_connections_bad_total 104167
telemt_connections_current 2069
telemt_connections_me_current 2069
telemt_handshake_timeouts_total 30648
telemt_upstream_connect_attempt_total 5008
telemt_upstream_connect_success_total 4970
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3461
telemt_me_reconnect_success_total 3428
telemt_me_reader_eof_total 3604
telemt_me_idle_close_by_peer_total 3604
telemt_me_route_drop_no_conn_total 665085
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1534189
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8203
telemt_desync_full_logged_total 2551
telemt_desync_suppressed_total 5652
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 2866
telemt_desync_frames_bucket_total{bucket="gt_10"} 3818
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3491
telemt_me_writer_restored_same_endpoint_total 3411
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 1533344
telemt_user_connections_current{user="hello"} 2069
telemt_user_octets_from_client{user="hello"} 26128725440 (24.33 GB)
telemt_user_octets_to_client{user="hello"} 750401750128 (698.87 GB)
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 221
```