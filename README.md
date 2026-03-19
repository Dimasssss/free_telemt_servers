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

# Server Metrics 2026-03-19 18:22:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 3896.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123188
telemt_connections_bad_total 3905
telemt_connections_current 1517
telemt_connections_me_current 1517
telemt_handshake_timeouts_total 1259
telemt_upstream_connect_attempt_total 595
telemt_upstream_connect_success_total 586
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 347
telemt_me_reconnect_success_total 345
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 41286
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104869
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 465
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 332
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 105088
telemt_user_connections_current{user="hello"} 1517
telemt_user_octets_from_client{user="hello"} 1722853240 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 35196217820 (32.78 GB)
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 20352.3 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2021681
telemt_connections_bad_total 98311
telemt_connections_current 3735
telemt_connections_me_current 3735
telemt_handshake_timeouts_total 37705
telemt_upstream_connect_attempt_total 4687
telemt_upstream_connect_success_total 4627
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 4687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6572
telemt_me_reconnect_success_total 2347
telemt_me_reader_eof_total 2529
telemt_me_idle_close_by_peer_total 2529
telemt_me_route_drop_no_conn_total 1156019
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1682718
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6839
telemt_desync_full_logged_total 2168
telemt_desync_suppressed_total 4671
telemt_desync_frames_bucket_total{bucket="1_2"} 1305
telemt_desync_frames_bucket_total{bucket="3_10"} 2717
telemt_desync_frames_bucket_total{bucket="gt_10"} 2817
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2493
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2292
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1682704
telemt_user_connections_current{user="hello"} 3735
telemt_user_octets_from_client{user="hello"} 24675914126 (22.98 GB)
telemt_user_octets_to_client{user="hello"} 547817399262 (510.19 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1307
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 20330.5 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1853608
telemt_connections_bad_total 220426
telemt_connections_current 2737
telemt_connections_me_current 2737
telemt_handshake_timeouts_total 20149
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3196
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3063
telemt_me_reconnect_success_total 2145
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2184
telemt_me_route_drop_no_conn_total 1591894
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1409198
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4537
telemt_desync_full_logged_total 1359
telemt_desync_suppressed_total 3178
telemt_desync_frames_bucket_total{bucket="1_2"} 1183
telemt_desync_frames_bucket_total{bucket="3_10"} 1711
telemt_desync_frames_bucket_total{bucket="gt_10"} 1643
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 2136
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1406183
telemt_user_connections_current{user="hello"} 2737
telemt_user_octets_from_client{user="hello"} 18218890900 (16.97 GB)
telemt_user_octets_to_client{user="hello"} 446082943480 (415.45 GB)
telemt_user_unique_ips_current{user="hello"} 942
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 20318.2 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1727724
telemt_connections_bad_total 59316
telemt_connections_current 2873
telemt_connections_me_current 2873
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 23561
telemt_upstream_connect_attempt_total 25207
telemt_upstream_connect_success_total 24029
telemt_upstream_connect_fail_total 1178
telemt_upstream_connect_attempts_per_request{bucket="1"} 25207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1178
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4924
telemt_me_reconnect_success_total 2552
telemt_me_reader_eof_total 2635
telemt_me_idle_close_by_peer_total 2634
telemt_me_route_drop_no_conn_total 1504130
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489925
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5877
telemt_desync_full_logged_total 1831
telemt_desync_suppressed_total 4046
telemt_desync_frames_bucket_total{bucket="1_2"} 1558
telemt_desync_frames_bucket_total{bucket="3_10"} 2165
telemt_desync_frames_bucket_total{bucket="gt_10"} 2154
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 2958
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2548
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 1509267
telemt_user_connections_current{user="hello"} 2873
telemt_user_octets_from_client{user="hello"} 26560570753 (24.74 GB)
telemt_user_octets_to_client{user="hello"} 327434155957 (304.95 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 74041.7 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5414105
telemt_connections_bad_total 999491
telemt_connections_current 3033
telemt_connections_me_current 3033
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 98885
telemt_upstream_connect_attempt_total 64840
telemt_upstream_connect_success_total 62347
telemt_upstream_connect_fail_total 2493
telemt_upstream_connect_attempts_per_request{bucket="1"} 64840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1047
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74851
telemt_me_reconnect_success_total 9443
telemt_me_reader_eof_total 9952
telemt_me_idle_close_by_peer_total 9949
telemt_me_route_drop_no_conn_total 2489056
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3752824
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
telemt_desync_total 16324
telemt_desync_full_logged_total 5004
telemt_desync_suppressed_total 11320
telemt_desync_frames_bucket_total{bucket="1_2"} 2682
telemt_desync_frames_bucket_total{bucket="3_10"} 6822
telemt_desync_frames_bucket_total{bucket="gt_10"} 6820
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 9684
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9419
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 3800935
telemt_user_connections_current{user="hello"} 3033
telemt_user_octets_from_client{user="hello"} 59241349115 (55.17 GB)
telemt_user_octets_to_client{user="hello"} 1395485790380 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1084
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 20282.3 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484961
telemt_connections_bad_total 32370
telemt_connections_current 620
telemt_connections_me_current 620
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 9971
telemt_upstream_connect_attempt_total 7010
telemt_upstream_connect_success_total 6813
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 2826
telemt_me_reconnect_success_total 2770
telemt_me_reader_eof_total 2838
telemt_me_idle_close_by_peer_total 2837
telemt_me_route_drop_no_conn_total 352324
telemt_me_route_drop_channel_closed_total 122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383658
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
telemt_desync_total 1027
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 700
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 416
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2788
telemt_me_writer_restored_same_endpoint_total 2761
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 402314
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 4671555512 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 84628042486 (78.82 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 20282.7 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1340378
telemt_connections_bad_total 85671
telemt_connections_current 2989
telemt_connections_me_current 2989
telemt_handshake_timeouts_total 23804
telemt_upstream_connect_attempt_total 3365
telemt_upstream_connect_success_total 3339
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2307
telemt_me_reconnect_success_total 2282
telemt_me_reader_eof_total 2390
telemt_me_idle_close_by_peer_total 2390
telemt_me_route_drop_no_conn_total 519778
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1157746
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6208
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 4320
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 2154
telemt_desync_frames_bucket_total{bucket="gt_10"} 2840
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 2327
telemt_me_writer_restored_same_endpoint_total 2265
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 1157037
telemt_user_connections_current{user="hello"} 2989
telemt_user_octets_from_client{user="hello"} 17962287056 (16.73 GB)
telemt_user_octets_to_client{user="hello"} 509484478516 (474.49 GB)
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 363
```