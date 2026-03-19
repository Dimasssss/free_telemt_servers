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

# Server Metrics 2026-03-19 22:15:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 17853.7 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411116
telemt_connections_bad_total 21468
telemt_connections_current 849
telemt_connections_me_current 849
telemt_handshake_timeouts_total 5952
telemt_upstream_connect_attempt_total 2923
telemt_upstream_connect_success_total 2896
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2012
telemt_me_reconnect_success_total 1997
telemt_me_reader_eof_total 2111
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 123968
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327341
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1775
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 2040
telemt_me_writer_restored_same_endpoint_total 1984
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 327623
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 11526504304 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 121579663488 (113.23 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 34308.0 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2762416
telemt_connections_bad_total 119283
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_handshake_timeouts_total 54792
telemt_upstream_connect_attempt_total 6998
telemt_upstream_connect_success_total 6887
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 6998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8140
telemt_me_reconnect_success_total 3909
telemt_me_reader_eof_total 4196
telemt_me_idle_close_by_peer_total 4196
telemt_me_route_drop_no_conn_total 1436966
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2357515
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10463
telemt_desync_full_logged_total 3412
telemt_desync_suppressed_total 7051
telemt_desync_frames_bucket_total{bucket="1_2"} 1945
telemt_desync_frames_bucket_total{bucket="3_10"} 4085
telemt_desync_frames_bucket_total{bucket="gt_10"} 4433
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 4078
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3854
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 2357392
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 37411408606 (34.84 GB)
telemt_user_octets_to_client{user="hello"} 843234200854 (785.32 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 34286.2 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2690734
telemt_connections_bad_total 459240
telemt_connections_current 1301
telemt_connections_me_current 1301
telemt_handshake_timeouts_total 34356
telemt_upstream_connect_attempt_total 5361
telemt_upstream_connect_success_total 5318
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 5361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4503
telemt_me_reconnect_success_total 3575
telemt_me_reader_eof_total 3718
telemt_me_idle_close_by_peer_total 3717
telemt_me_route_drop_no_conn_total 1859654
telemt_me_route_drop_channel_closed_total 166
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1878834
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7327
telemt_desync_full_logged_total 2203
telemt_desync_suppressed_total 5124
telemt_desync_frames_bucket_total{bucket="1_2"} 1810
telemt_desync_frames_bucket_total{bucket="3_10"} 2798
telemt_desync_frames_bucket_total{bucket="gt_10"} 2719
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 61
telemt_me_writer_removed_unexpected_total 3600
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3574
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1874759
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 28415105116 (26.46 GB)
telemt_user_octets_to_client{user="hello"} 691324963604 (643.85 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 34274.0 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2359627
telemt_connections_bad_total 99165
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29369
telemt_upstream_connect_attempt_total 35719
telemt_upstream_connect_success_total 33983
telemt_upstream_connect_fail_total 1736
telemt_upstream_connect_attempts_per_request{bucket="1"} 35719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1736
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6788
telemt_me_reconnect_success_total 4166
telemt_me_reader_eof_total 4310
telemt_me_idle_close_by_peer_total 4309
telemt_me_route_drop_no_conn_total 1822061
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2002970
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8054
telemt_desync_full_logged_total 2521
telemt_desync_suppressed_total 5533
telemt_desync_frames_bucket_total{bucket="1_2"} 1978
telemt_desync_frames_bucket_total{bucket="3_10"} 2922
telemt_desync_frames_bucket_total{bucket="gt_10"} 3154
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4686
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4162
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 2029901
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 33342068276 (31.05 GB)
telemt_user_octets_to_client{user="hello"} 526752468071 (490.58 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 87997.1 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6029781
telemt_connections_bad_total 1036210
telemt_connections_current 1678
telemt_connections_me_current 1678
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109028
telemt_upstream_connect_attempt_total 66972
telemt_upstream_connect_success_total 64466
telemt_upstream_connect_fail_total 2506
telemt_upstream_connect_attempts_per_request{bucket="1"} 66972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2506
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76323
telemt_me_reconnect_success_total 10904
telemt_me_reader_eof_total 11511
telemt_me_idle_close_by_peer_total 11508
telemt_me_route_drop_no_conn_total 2746005
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4280973
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
telemt_desync_total 18892
telemt_desync_full_logged_total 5867
telemt_desync_suppressed_total 13025
telemt_desync_frames_bucket_total{bucket="1_2"} 3298
telemt_desync_frames_bucket_total{bucket="3_10"} 7766
telemt_desync_frames_bucket_total{bucket="gt_10"} 7828
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 11169
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10880
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 4329022
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 67076187283 (62.47 GB)
telemt_user_octets_to_client{user="hello"} 1674962848932 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 34237.1 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630009
telemt_connections_bad_total 49746
telemt_connections_current 398
telemt_connections_me_current 398
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12048
telemt_upstream_connect_attempt_total 9439
telemt_upstream_connect_success_total 9226
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4598
telemt_me_reconnect_success_total 4519
telemt_me_reader_eof_total 4706
telemt_me_idle_close_by_peer_total 4704
telemt_me_route_drop_no_conn_total 443887
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532039
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
telemt_desync_total 1355
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 848
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4560
telemt_me_writer_restored_same_endpoint_total 4510
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 521165
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 6859994864 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 124061140102 (115.54 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 34238.5 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1865044
telemt_connections_bad_total 108938
telemt_connections_current 1391
telemt_connections_me_current 1391
telemt_handshake_timeouts_total 34304
telemt_upstream_connect_attempt_total 5707
telemt_upstream_connect_success_total 5666
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3974
telemt_me_reconnect_success_total 3939
telemt_me_reader_eof_total 4147
telemt_me_idle_close_by_peer_total 4147
telemt_me_route_drop_no_conn_total 697166
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1616851
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8651
telemt_desync_full_logged_total 2728
telemt_desync_suppressed_total 5923
telemt_desync_frames_bucket_total{bucket="1_2"} 1588
telemt_desync_frames_bucket_total{bucket="3_10"} 3016
telemt_desync_frames_bucket_total{bucket="gt_10"} 4047
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4011
telemt_me_writer_restored_same_endpoint_total 3922
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1615995
telemt_user_connections_current{user="hello"} 1391
telemt_user_octets_from_client{user="hello"} 27570279684 (25.68 GB)
telemt_user_octets_to_client{user="hello"} 808079786728 (752.58 GB)
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 123
```