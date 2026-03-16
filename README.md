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

# Server Metrics 2026-03-16 03:23:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 104946.8 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450933
telemt_connections_bad_total 5373
telemt_handshake_timeouts_total 15471
telemt_upstream_connect_attempt_total 25089
telemt_upstream_connect_success_total 24974
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 25089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 23195
telemt_me_reconnect_success_total 19773
telemt_me_reader_eof_total 21145
telemt_me_idle_close_by_peer_total 21145
telemt_me_route_drop_no_conn_total 500549
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473383
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2305
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 938
telemt_pool_swap_total 100
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20094
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 19739
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 412237
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 8499596740 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 293185679312 (273.05 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 104953.0 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182844
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 14635
telemt_upstream_connect_attempt_total 28625
telemt_upstream_connect_success_total 28550
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 28625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 29842
telemt_me_reconnect_success_total 22936
telemt_me_reader_eof_total 24571
telemt_me_idle_close_by_peer_total 24570
telemt_me_route_drop_no_conn_total 92800
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158596
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 23472
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 22920
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 158142
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3466543573 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 81574979216 (75.97 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 104945.7 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202378
telemt_connections_bad_total 2971
telemt_handshake_timeouts_total 3931
telemt_upstream_connect_attempt_total 29693
telemt_upstream_connect_success_total 29685
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 31810
telemt_me_reconnect_success_total 24422
telemt_me_reader_eof_total 26300
telemt_me_idle_close_by_peer_total 26299
telemt_me_route_drop_no_conn_total 71650
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161260
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 24893
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 24414
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 160992
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 16425548973 (15.30 GB)
telemt_user_octets_to_client{user="hello"} 101427138396 (94.46 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 104945.5 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266750
telemt_connections_bad_total 1224
telemt_handshake_timeouts_total 1689
telemt_upstream_connect_attempt_total 24627
telemt_upstream_connect_success_total 24606
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 24627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19517
telemt_me_reconnect_success_total 19402
telemt_me_reader_eof_total 20710
telemt_me_idle_close_by_peer_total 20709
telemt_me_route_drop_no_conn_total 97990
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246544
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 881
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19637
telemt_me_writer_restored_same_endpoint_total 19391
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 246426
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 4230791064 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 111894358848 (104.21 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 80016.9 (22h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176675
telemt_connections_bad_total 31248
telemt_handshake_timeouts_total 3099
telemt_upstream_connect_attempt_total 22811
telemt_upstream_connect_success_total 22686
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 22811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 113028
telemt_me_reconnect_success_total 18557
telemt_me_reader_eof_total 19696
telemt_me_idle_close_by_peer_total 19696
telemt_me_route_drop_no_conn_total 55897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138010
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 18702
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 18453
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 137650
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 1941615941 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 59354126979 (55.28 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 104944.7 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676947
telemt_connections_bad_total 58740
telemt_handshake_timeouts_total 5046
telemt_upstream_connect_attempt_total 22302
telemt_upstream_connect_success_total 22183
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 22302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 18284
telemt_me_reconnect_success_total 16952
telemt_me_reader_eof_total 18091
telemt_me_idle_close_by_peer_total 18091
telemt_me_route_drop_no_conn_total 594312
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701368
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17190
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 16925
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 560046
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 12989277868 (12.10 GB)
telemt_user_octets_to_client{user="hello"} 344802891252 (321.12 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 36
```