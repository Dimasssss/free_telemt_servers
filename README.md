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

# Server Metrics 2026-03-19 17:26:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 515.6 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21983
telemt_connections_bad_total 443
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_handshake_timeouts_total 291
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 110
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 5398
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19251
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 19252
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 146753524 (139.96 MB)
telemt_user_octets_to_client{user="hello"} 5095285228 (4.75 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 16971.2 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1744854
telemt_connections_bad_total 88475
telemt_connections_current 3771
telemt_connections_me_current 3771
telemt_handshake_timeouts_total 33063
telemt_upstream_connect_attempt_total 4148
telemt_upstream_connect_success_total 4098
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 4148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6215
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2155
telemt_me_route_drop_no_conn_total 1043479
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1435507
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5522
telemt_desync_full_logged_total 1711
telemt_desync_suppressed_total 3811
telemt_desync_frames_bucket_total{bucket="1_2"} 1096
telemt_desync_frames_bucket_total{bucket="3_10"} 2161
telemt_desync_frames_bucket_total{bucket="gt_10"} 2265
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2133
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1937
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 1435513
telemt_user_connections_current{user="hello"} 3771
telemt_user_octets_from_client{user="hello"} 21335937938 (19.87 GB)
telemt_user_octets_to_client{user="hello"} 451628158738 (420.61 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 542
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 16949.9 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1625102
telemt_connections_bad_total 199102
telemt_connections_current 2848
telemt_connections_me_current 2848
telemt_handshake_timeouts_total 16723
telemt_upstream_connect_attempt_total 2723
telemt_upstream_connect_success_total 2704
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2743
telemt_me_reconnect_success_total 1825
telemt_me_reader_eof_total 1842
telemt_me_idle_close_by_peer_total 1841
telemt_me_route_drop_no_conn_total 1510933
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1230430
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3929
telemt_desync_full_logged_total 1147
telemt_desync_suppressed_total 2782
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1466
telemt_desync_frames_bucket_total{bucket="gt_10"} 1417
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1812
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1824
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1227649
telemt_user_connections_current{user="hello"} 2848
telemt_user_octets_from_client{user="hello"} 14728903888 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 363176519172 (338.23 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 16937.0 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1389991
telemt_connections_bad_total 56828
telemt_connections_current 2892
telemt_connections_me_current 2892
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 20698
telemt_upstream_connect_attempt_total 19855
telemt_upstream_connect_success_total 18940
telemt_upstream_connect_fail_total 915
telemt_upstream_connect_attempts_per_request{bucket="1"} 19855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 915
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4390
telemt_me_reconnect_success_total 2125
telemt_me_reader_eof_total 2198
telemt_me_idle_close_by_peer_total 2197
telemt_me_route_drop_no_conn_total 1059445
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1191686
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1545
telemt_desync_suppressed_total 3423
telemt_desync_frames_bucket_total{bucket="1_2"} 1317
telemt_desync_frames_bucket_total{bucket="3_10"} 1835
telemt_desync_frames_bucket_total{bucket="gt_10"} 1816
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2454
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2121
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 1206989
telemt_user_connections_current{user="hello"} 2892
telemt_user_octets_from_client{user="hello"} 23207251265 (21.61 GB)
telemt_user_octets_to_client{user="hello"} 276167074814 (257.20 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 990
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 70660.5 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5068909
telemt_connections_bad_total 875237
telemt_connections_current 3629
telemt_connections_me_current 3629
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 95941
telemt_upstream_connect_attempt_total 64370
telemt_upstream_connect_success_total 61879
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1037
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74557
telemt_me_reconnect_success_total 9152
telemt_me_reader_eof_total 9638
telemt_me_idle_close_by_peer_total 9635
telemt_me_route_drop_no_conn_total 2398012
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3558379
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
telemt_desync_total 15572
telemt_desync_full_logged_total 4735
telemt_desync_suppressed_total 10837
telemt_desync_frames_bucket_total{bucket="1_2"} 2541
telemt_desync_frames_bucket_total{bucket="3_10"} 6536
telemt_desync_frames_bucket_total{bucket="gt_10"} 6495
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 9387
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9128
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 3606522
telemt_user_connections_current{user="hello"} 3629
telemt_user_octets_from_client{user="hello"} 56367927899 (52.50 GB)
telemt_user_octets_to_client{user="hello"} 1309364693328 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 16901.5 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350672
telemt_connections_bad_total 26715
telemt_connections_current 843
telemt_connections_me_current 843
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7659
telemt_upstream_connect_attempt_total 5976
telemt_upstream_connect_success_total 5839
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 5976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 2459
telemt_me_reconnect_success_total 2420
telemt_me_reader_eof_total 2464
telemt_me_idle_close_by_peer_total 2464
telemt_me_route_drop_no_conn_total 211349
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295653
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 930
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 430
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 63
telemt_me_writer_removed_unexpected_total 2409
telemt_me_writer_restored_same_endpoint_total 2411
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 298227
telemt_user_connections_current{user="hello"} 843
telemt_user_octets_from_client{user="hello"} 4128511760 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 77325068294 (72.01 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 16901.6 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1139783
telemt_connections_bad_total 78086
telemt_connections_current 3172
telemt_connections_me_current 3172
telemt_handshake_timeouts_total 19364
telemt_upstream_connect_attempt_total 2859
telemt_upstream_connect_success_total 2837
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1977
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 2039
telemt_me_idle_close_by_peer_total 2039
telemt_me_route_drop_no_conn_total 450578
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976608
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5452
telemt_desync_full_logged_total 1643
telemt_desync_suppressed_total 3809
telemt_desync_frames_bucket_total{bucket="1_2"} 1106
telemt_desync_frames_bucket_total{bucket="3_10"} 1874
telemt_desync_frames_bucket_total{bucket="gt_10"} 2472
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1993
telemt_me_writer_restored_same_endpoint_total 1935
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 976157
telemt_user_connections_current{user="hello"} 3172
telemt_user_octets_from_client{user="hello"} 15003579700 (13.97 GB)
telemt_user_octets_to_client{user="hello"} 420954819432 (392.04 GB)
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 391
```