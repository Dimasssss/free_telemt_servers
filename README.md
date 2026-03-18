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

# Server Metrics 2026-03-18 20:10:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17095.0 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426270
telemt_connections_bad_total 24877
telemt_handshake_timeouts_total 9185
telemt_upstream_connect_attempt_total 3023
telemt_upstream_connect_success_total 3020
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 2173
telemt_me_reconnect_success_total 2159
telemt_me_reader_eof_total 2251
telemt_me_idle_close_by_peer_total 2251
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 180275
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368857
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2184
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 1558
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 694
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2202
telemt_me_writer_restored_same_endpoint_total 2141
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 368677
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 7279843748 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 132538807660 (123.44 GB)
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 21923.5 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2026052
telemt_connections_bad_total 140477
telemt_connections_current 3278
telemt_connections_me_current 3278
telemt_handshake_timeouts_total 34960
telemt_upstream_connect_attempt_total 3468
telemt_upstream_connect_success_total 3449
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2342
telemt_me_reconnect_success_total 2325
telemt_me_reader_eof_total 2352
telemt_me_idle_close_by_peer_total 2351
telemt_me_route_drop_no_conn_total 1794641
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1753081
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6143
telemt_desync_full_logged_total 1980
telemt_desync_suppressed_total 4163
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 2437
telemt_desync_frames_bucket_total{bucket="gt_10"} 2643
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2285
telemt_me_writer_restored_same_endpoint_total 2323
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1748394
telemt_user_connections_current{user="hello"} 3278
telemt_user_octets_from_client{user="hello"} 26924892484 (25.08 GB)
telemt_user_octets_to_client{user="hello"} 587535142048 (547.18 GB)
telemt_user_unique_ips_current{user="hello"} 1071
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 21852.2 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1543710
telemt_connections_bad_total 127232
telemt_connections_current 2650
telemt_connections_me_current 2650
telemt_handshake_timeouts_total 35227
telemt_upstream_connect_attempt_total 3151
telemt_upstream_connect_success_total 3134
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2023
telemt_me_reconnect_success_total 2005
telemt_me_reader_eof_total 2132
telemt_me_idle_close_by_peer_total 2132
telemt_me_route_drop_no_conn_total 626296
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1239382
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5962
telemt_desync_full_logged_total 1832
telemt_desync_suppressed_total 4130
telemt_desync_frames_bucket_total{bucket="1_2"} 1496
telemt_desync_frames_bucket_total{bucket="3_10"} 2250
telemt_desync_frames_bucket_total{bucket="gt_10"} 2216
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2056
telemt_me_writer_restored_same_endpoint_total 1988
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1238583
telemt_user_connections_current{user="hello"} 2650
telemt_user_octets_from_client{user="hello"} 26757164132 (24.92 GB)
telemt_user_octets_to_client{user="hello"} 616291489236 (573.97 GB)
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 22566.6 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2180982
telemt_connections_bad_total 58654
telemt_connections_current 2299
telemt_connections_me_current 2299
telemt_handshake_timeouts_total 21963
telemt_upstream_connect_attempt_total 3396
telemt_upstream_connect_success_total 3361
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2224
telemt_me_reconnect_success_total 2197
telemt_me_reader_eof_total 2285
telemt_me_idle_close_by_peer_total 2284
telemt_me_route_drop_no_conn_total 3689501
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1949953
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7335
telemt_desync_full_logged_total 1895
telemt_desync_suppressed_total 5440
telemt_desync_frames_bucket_total{bucket="1_2"} 1602
telemt_desync_frames_bucket_total{bucket="3_10"} 3400
telemt_desync_frames_bucket_total{bucket="gt_10"} 2333
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2213
telemt_me_writer_restored_same_endpoint_total 2186
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1949860
telemt_user_connections_current{user="hello"} 2299
telemt_user_octets_from_client{user="hello"} 18252060352 (17.00 GB)
telemt_user_octets_to_client{user="hello"} 335284443612 (312.26 GB)
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17081.4 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1216719
telemt_connections_bad_total 218657
telemt_handshake_timeouts_total 11700
telemt_upstream_connect_attempt_total 3083
telemt_upstream_connect_success_total 2992
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 3083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 4229
telemt_me_reconnect_success_total 2132
telemt_me_reader_eof_total 2256
telemt_me_idle_close_by_peer_total 2256
telemt_me_route_drop_no_conn_total 516200
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892110
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3170
telemt_desync_full_logged_total 1140
telemt_desync_suppressed_total 2030
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 1087
telemt_desync_frames_bucket_total{bucket="gt_10"} 1497
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2234
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 2106
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 891472
telemt_user_connections_current{user="hello"} 2813
telemt_user_octets_from_client{user="hello"} 15525636432 (14.46 GB)
telemt_user_octets_to_client{user="hello"} 427352409008 (398.00 GB)
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 22014.8 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352557
telemt_connections_bad_total 10682
telemt_connections_current 639
telemt_connections_me_current 639
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3970
telemt_upstream_connect_attempt_total 7846
telemt_upstream_connect_success_total 7814
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 332332
telemt_me_reconnect_success_total 2862
telemt_me_reader_eof_total 2923
telemt_me_idle_close_by_peer_total 2923
telemt_me_route_drop_no_conn_total 212432
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313102
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 652
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2821
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2851
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 316787
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 6565815353 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 73160021597 (68.14 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 21085.7 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235537
telemt_connections_bad_total 99897
telemt_connections_current 2594
telemt_connections_me_current 2594
telemt_handshake_timeouts_total 25168
telemt_upstream_connect_attempt_total 3510
telemt_upstream_connect_success_total 3509
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17943
telemt_me_reconnect_success_total 2422
telemt_me_reader_eof_total 2473
telemt_me_idle_close_by_peer_total 2473
telemt_me_route_drop_no_conn_total 557639
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1030435
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4573
telemt_desync_full_logged_total 1522
telemt_desync_suppressed_total 3051
telemt_desync_frames_bucket_total{bucket="1_2"} 1049
telemt_desync_frames_bucket_total{bucket="3_10"} 1580
telemt_desync_frames_bucket_total{bucket="gt_10"} 1944
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2405
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2361
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1029212
telemt_user_connections_current{user="hello"} 2594
telemt_user_octets_from_client{user="hello"} 20527162544 (19.12 GB)
telemt_user_octets_to_client{user="hello"} 593402018932 (552.65 GB)
telemt_user_unique_ips_current{user="hello"} 819
telemt_user_unique_ips_recent_window{user="hello"} 290
```