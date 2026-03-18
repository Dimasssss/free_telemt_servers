# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-18 12:49:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 14915.8 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546102
telemt_connections_bad_total 15228
telemt_handshake_timeouts_total 15137
telemt_upstream_connect_attempt_total 65963
telemt_upstream_connect_success_total 65014
telemt_upstream_connect_fail_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 65963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 949
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 512637
telemt_me_reconnect_success_total 2270
telemt_me_reader_eof_total 2378
telemt_me_idle_close_by_peer_total 2376
telemt_me_route_drop_no_conn_total 325145
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417839
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1802
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2393
telemt_me_refill_failed_total 16632
telemt_me_writer_restored_same_endpoint_total 2165
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 476073
telemt_user_connections_current{user="hello"} 1851
telemt_user_octets_from_client{user="hello"} 6481583240 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 123131827509 (114.68 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 14946.5 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484985
telemt_connections_bad_total 109745
telemt_handshake_timeouts_total 33449
telemt_upstream_connect_attempt_total 2660
telemt_upstream_connect_success_total 2648
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 2963
telemt_me_reconnect_success_total 1826
telemt_me_reader_eof_total 1887
telemt_me_idle_close_by_peer_total 1886
telemt_me_route_drop_no_conn_total 1266666
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4003
telemt_desync_full_logged_total 1214
telemt_desync_suppressed_total 2789
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1596
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1869
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1825
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1271349
telemt_user_connections_current{user="hello"} 4179
telemt_user_octets_from_client{user="hello"} 31285215600 (29.14 GB)
telemt_user_octets_to_client{user="hello"} 375724345088 (349.92 GB)
telemt_user_unique_ips_current{user="hello"} 1266
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 14861.3 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056341
telemt_connections_bad_total 76333
telemt_handshake_timeouts_total 25585
telemt_upstream_connect_attempt_total 11048
telemt_upstream_connect_success_total 11048
telemt_upstream_connect_attempts_per_request{bucket="1"} 11048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607733
telemt_me_reconnect_success_total 2036
telemt_me_reader_eof_total 2065
telemt_me_idle_close_by_peer_total 2064
telemt_me_route_drop_no_conn_total 446367
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806636
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2325
telemt_desync_full_logged_total 803
telemt_desync_suppressed_total 1522
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 862
telemt_desync_frames_bucket_total{bucket="gt_10"} 817
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2049
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 2001
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 814136
telemt_user_connections_current{user="hello"} 3270
telemt_user_octets_from_client{user="hello"} 9786633139 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 337119985952 (313.97 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1003
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 14891.5 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1747929
telemt_connections_bad_total 24533
telemt_handshake_timeouts_total 166872
telemt_upstream_connect_attempt_total 12437
telemt_upstream_connect_success_total 12248
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 12437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2829837
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1720
telemt_me_idle_close_by_peer_total 1720
telemt_me_route_drop_no_conn_total 2618021
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414930
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2950
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 2032
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 1227
telemt_desync_frames_bucket_total{bucket="gt_10"} 987
telemt_me_writer_removed_unexpected_total 1767
telemt_me_refill_failed_total 100133
telemt_me_writer_restored_same_endpoint_total 1084
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 1433515
telemt_user_connections_current{user="hello"} 3345
telemt_user_octets_from_client{user="hello"} 20641292158 (19.22 GB)
telemt_user_octets_to_client{user="hello"} 217612696329 (202.67 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 918
telemt_user_unique_ips_recent_window{user="hello"} 521
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 14786.4 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097115
telemt_connections_bad_total 47465
telemt_handshake_timeouts_total 19016
telemt_upstream_connect_attempt_total 12110
telemt_upstream_connect_success_total 12109
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2984931
telemt_me_reconnect_success_total 1814
telemt_me_reader_eof_total 1852
telemt_me_idle_close_by_peer_total 1852
telemt_me_route_drop_no_conn_total 686801
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935513
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3090
telemt_desync_full_logged_total 1037
telemt_desync_suppressed_total 2053
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 1211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1441
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1829
telemt_me_refill_failed_total 107189
telemt_me_writer_restored_same_endpoint_total 1699
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 935686
telemt_user_connections_current{user="hello"} 3133
telemt_user_octets_from_client{user="hello"} 14711576081 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 355077729657 (330.69 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 14672.8 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315422
telemt_connections_bad_total 29987
telemt_handshake_timeouts_total 2417
telemt_upstream_connect_attempt_total 2833
telemt_upstream_connect_success_total 2833
telemt_upstream_connect_attempts_per_request{bucket="1"} 2833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7122
telemt_me_reconnect_success_total 2012
telemt_me_reader_eof_total 2207
telemt_me_idle_close_by_peer_total 2206
telemt_me_route_drop_no_conn_total 169948
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269687
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 682
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2189
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 2004
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 259976
telemt_user_connections_current{user="hello"} 979
telemt_user_octets_from_client{user="hello"} 4408911976 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 55293739608 (51.50 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 14742.4 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903349
telemt_connections_bad_total 116599
telemt_handshake_timeouts_total 19170
telemt_upstream_connect_attempt_total 2705
telemt_upstream_connect_success_total 2678
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 1899
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1918
telemt_me_idle_close_by_peer_total 1918
telemt_me_route_drop_no_conn_total 413196
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698018
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2503
telemt_desync_full_logged_total 854
telemt_desync_suppressed_total 1649
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 1208
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1881
telemt_me_writer_restored_same_endpoint_total 1858
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 697503
telemt_user_connections_current{user="hello"} 2740
telemt_user_octets_from_client{user="hello"} 14969938000 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 340268191200 (316.90 GB)
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 363
```