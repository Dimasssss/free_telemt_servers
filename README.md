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

# Server Metrics 2026-03-19 22:25:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 18464.4 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421003
telemt_connections_bad_total 24766
telemt_connections_current 798
telemt_connections_me_current 798
telemt_handshake_timeouts_total 6049
telemt_upstream_connect_attempt_total 3046
telemt_upstream_connect_success_total 3018
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2091
telemt_me_reconnect_success_total 2075
telemt_me_reader_eof_total 2198
telemt_me_idle_close_by_peer_total 2198
telemt_me_route_drop_no_conn_total 125849
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333487
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1802
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1172
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 2119
telemt_me_writer_restored_same_endpoint_total 2062
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 333761
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 12178619796 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 124235930124 (115.70 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 34919.7 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2778230
telemt_connections_bad_total 119868
telemt_connections_current 1646
telemt_connections_me_current 1646
telemt_handshake_timeouts_total 55559
telemt_upstream_connect_attempt_total 7097
telemt_upstream_connect_success_total 6986
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 7097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8239
telemt_me_reconnect_success_total 4008
telemt_me_reader_eof_total 4301
telemt_me_idle_close_by_peer_total 4301
telemt_me_route_drop_no_conn_total 1441968
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2371446
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10520
telemt_desync_full_logged_total 3441
telemt_desync_suppressed_total 7079
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 4112
telemt_desync_frames_bucket_total{bucket="gt_10"} 4453
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 4177
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3953
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 2371323
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 37535319770 (34.96 GB)
telemt_user_octets_to_client{user="hello"} 849966643742 (791.59 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 34898.0 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2704936
telemt_connections_bad_total 459969
telemt_connections_current 1412
telemt_connections_me_current 1412
telemt_handshake_timeouts_total 34658
telemt_upstream_connect_attempt_total 5463
telemt_upstream_connect_success_total 5419
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 5463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4596
telemt_me_reconnect_success_total 3668
telemt_me_reader_eof_total 3817
telemt_me_idle_close_by_peer_total 3816
telemt_me_route_drop_no_conn_total 1863140
telemt_me_route_drop_channel_closed_total 167
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1888179
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7363
telemt_desync_full_logged_total 2219
telemt_desync_suppressed_total 5144
telemt_desync_frames_bucket_total{bucket="1_2"} 1817
telemt_desync_frames_bucket_total{bucket="3_10"} 2814
telemt_desync_frames_bucket_total{bucket="gt_10"} 2732
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 61
telemt_me_writer_removed_unexpected_total 3695
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1884104
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 28506746668 (26.55 GB)
telemt_user_octets_to_client{user="hello"} 696992842356 (649.13 GB)
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 34885.6 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2369299
telemt_connections_bad_total 99333
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29437
telemt_upstream_connect_attempt_total 35833
telemt_upstream_connect_success_total 34089
telemt_upstream_connect_fail_total 1744
telemt_upstream_connect_attempts_per_request{bucket="1"} 35833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1744
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6887
telemt_me_reconnect_success_total 4259
telemt_me_reader_eof_total 4418
telemt_me_idle_close_by_peer_total 4417
telemt_me_route_drop_no_conn_total 1825551
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2011993
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8079
telemt_desync_full_logged_total 2536
telemt_desync_suppressed_total 5543
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 2935
telemt_desync_frames_bucket_total{bucket="gt_10"} 3161
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4782
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4255
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 2038924
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 33414051424 (31.12 GB)
telemt_user_octets_to_client{user="hello"} 529820560763 (493.43 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 88608.7 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6043019
telemt_connections_bad_total 1036457
telemt_connections_current 1613
telemt_connections_me_current 1613
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109346
telemt_upstream_connect_attempt_total 67107
telemt_upstream_connect_success_total 64600
telemt_upstream_connect_fail_total 2507
telemt_upstream_connect_attempts_per_request{bucket="1"} 67107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2507
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76414
telemt_me_reconnect_success_total 10995
telemt_me_reader_eof_total 11612
telemt_me_idle_close_by_peer_total 11609
telemt_me_route_drop_no_conn_total 2750242
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4293111
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
telemt_desync_total 18917
telemt_desync_full_logged_total 5877
telemt_desync_suppressed_total 13040
telemt_desync_frames_bucket_total{bucket="1_2"} 3305
telemt_desync_frames_bucket_total{bucket="3_10"} 7773
telemt_desync_frames_bucket_total{bucket="gt_10"} 7839
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 11262
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10971
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 4341160
telemt_user_connections_current{user="hello"} 1613
telemt_user_octets_from_client{user="hello"} 67196075663 (62.58 GB)
telemt_user_octets_to_client{user="hello"} 1681011782000 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 34848.7 (9h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633739
telemt_connections_bad_total 50016
telemt_connections_current 392
telemt_connections_me_current 392
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12291
telemt_upstream_connect_attempt_total 9582
telemt_upstream_connect_success_total 9369
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 566
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4706
telemt_me_reconnect_success_total 4627
telemt_me_reader_eof_total 4823
telemt_me_idle_close_by_peer_total 4821
telemt_me_route_drop_no_conn_total 448173
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537440
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
telemt_desync_total 1362
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 146
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4668
telemt_me_writer_restored_same_endpoint_total 4618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 524107
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 6897773064 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 126298274546 (117.62 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 34850.0 (9h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1875884
telemt_connections_bad_total 108998
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_handshake_timeouts_total 34687
telemt_upstream_connect_attempt_total 5856
telemt_upstream_connect_success_total 5812
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 5856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4088
telemt_me_reconnect_success_total 4053
telemt_me_reader_eof_total 4267
telemt_me_idle_close_by_peer_total 4267
telemt_me_route_drop_no_conn_total 700900
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1625154
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8688
telemt_desync_full_logged_total 2744
telemt_desync_suppressed_total 5944
telemt_desync_frames_bucket_total{bucket="1_2"} 1597
telemt_desync_frames_bucket_total{bucket="3_10"} 3032
telemt_desync_frames_bucket_total{bucket="gt_10"} 4059
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4127
telemt_me_writer_restored_same_endpoint_total 4036
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1624298
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 27650170880 (25.75 GB)
telemt_user_octets_to_client{user="hello"} 813223394400 (757.37 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 108
```