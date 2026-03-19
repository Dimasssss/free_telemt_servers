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

# Server Metrics 2026-03-19 23:00:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 20604.6 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445477
telemt_connections_bad_total 28115
telemt_connections_current 815
telemt_connections_me_current 815
telemt_handshake_timeouts_total 6479
telemt_upstream_connect_attempt_total 3397
telemt_upstream_connect_success_total 3369
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2354
telemt_me_reconnect_success_total 2337
telemt_me_reader_eof_total 2477
telemt_me_idle_close_by_peer_total 2477
telemt_me_route_drop_no_conn_total 131918
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352863
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1894
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2386
telemt_me_writer_restored_same_endpoint_total 2324
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 353132
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 18364532236 (17.10 GB)
telemt_user_octets_to_client{user="hello"} 130934187068 (121.94 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 37059.8 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2831844
telemt_connections_bad_total 121179
telemt_connections_current 1535
telemt_connections_me_current 1535
telemt_handshake_timeouts_total 57642
telemt_upstream_connect_attempt_total 7460
telemt_upstream_connect_success_total 7342
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 7460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8466
telemt_me_reconnect_success_total 4234
telemt_me_reader_eof_total 4546
telemt_me_idle_close_by_peer_total 4546
telemt_me_route_drop_no_conn_total 1455830
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2419508
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10664
telemt_desync_full_logged_total 3504
telemt_desync_suppressed_total 7160
telemt_desync_frames_bucket_total{bucket="1_2"} 2000
telemt_desync_frames_bucket_total{bucket="3_10"} 4174
telemt_desync_frames_bucket_total{bucket="gt_10"} 4490
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 4409
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4179
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 2419385
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 37890643902 (35.29 GB)
telemt_user_octets_to_client{user="hello"} 870835674506 (811.03 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 37038.1 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755330
telemt_connections_bad_total 462531
telemt_connections_current 1156
telemt_connections_me_current 1156
telemt_handshake_timeouts_total 36137
telemt_upstream_connect_attempt_total 5823
telemt_upstream_connect_success_total 5776
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4824
telemt_me_reconnect_success_total 3894
telemt_me_reader_eof_total 4060
telemt_me_idle_close_by_peer_total 4059
telemt_me_route_drop_no_conn_total 1876757
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1920308
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7443
telemt_desync_full_logged_total 2253
telemt_desync_suppressed_total 5190
telemt_desync_frames_bucket_total{bucket="1_2"} 1826
telemt_desync_frames_bucket_total{bucket="3_10"} 2843
telemt_desync_frames_bucket_total{bucket="gt_10"} 2774
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 3926
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3893
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1916109
telemt_user_connections_current{user="hello"} 1156
telemt_user_octets_from_client{user="hello"} 28873805484 (26.89 GB)
telemt_user_octets_to_client{user="hello"} 720969080752 (671.45 GB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 37025.8 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2401342
telemt_connections_bad_total 100186
telemt_connections_current 1137
telemt_connections_me_current 1137
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29720
telemt_upstream_connect_attempt_total 36186
telemt_upstream_connect_success_total 34426
telemt_upstream_connect_fail_total 1760
telemt_upstream_connect_attempts_per_request{bucket="1"} 36186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 460
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1760
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7105
telemt_me_reconnect_success_total 4464
telemt_me_reader_eof_total 4635
telemt_me_idle_close_by_peer_total 4634
telemt_me_route_drop_no_conn_total 1837080
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2039439
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8137
telemt_desync_full_logged_total 2566
telemt_desync_suppressed_total 5571
telemt_desync_frames_bucket_total{bucket="1_2"} 1992
telemt_desync_frames_bucket_total{bucket="3_10"} 2959
telemt_desync_frames_bucket_total{bucket="gt_10"} 3186
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4994
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4460
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 2066370
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 33879844356 (31.55 GB)
telemt_user_octets_to_client{user="hello"} 547390113231 (509.80 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 90749.0 (25h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6080054
telemt_connections_bad_total 1036869
telemt_connections_current 1334
telemt_connections_me_current 1334
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 110034
telemt_upstream_connect_attempt_total 67466
telemt_upstream_connect_success_total 64957
telemt_upstream_connect_fail_total 2509
telemt_upstream_connect_attempts_per_request{bucket="1"} 67466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76685
telemt_me_reconnect_success_total 11266
telemt_me_reader_eof_total 11897
telemt_me_idle_close_by_peer_total 11894
telemt_me_route_drop_no_conn_total 2763147
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4327621
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
telemt_desync_total 19052
telemt_desync_full_logged_total 5951
telemt_desync_suppressed_total 13101
telemt_desync_frames_bucket_total{bucket="1_2"} 3330
telemt_desync_frames_bucket_total{bucket="3_10"} 7818
telemt_desync_frames_bucket_total{bucket="gt_10"} 7904
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 11535
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 11242
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 4375676
telemt_user_connections_current{user="hello"} 1334
telemt_user_octets_from_client{user="hello"} 67787120287 (63.13 GB)
telemt_user_octets_to_client{user="hello"} 1702170896168 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 36989.0 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646496
telemt_connections_bad_total 51420
telemt_connections_current 348
telemt_connections_me_current 348
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12713
telemt_upstream_connect_attempt_total 10365
telemt_upstream_connect_success_total 10124
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5011
telemt_me_reconnect_success_total 4925
telemt_me_reader_eof_total 5141
telemt_me_idle_close_by_peer_total 5139
telemt_me_route_drop_no_conn_total 452202
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547249
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
telemt_desync_total 1379
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 148
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4971
telemt_me_writer_restored_same_endpoint_total 4916
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 534237
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 7022570349 (6.54 GB)
telemt_user_octets_to_client{user="hello"} 129333672344 (120.45 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 36990.4 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1911989
telemt_connections_bad_total 115462
telemt_connections_current 1233
telemt_connections_me_current 1233
telemt_handshake_timeouts_total 35593
telemt_upstream_connect_attempt_total 6306
telemt_upstream_connect_success_total 6258
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4410
telemt_me_reconnect_success_total 4375
telemt_me_reader_eof_total 4606
telemt_me_idle_close_by_peer_total 4606
telemt_me_route_drop_no_conn_total 710745
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1650274
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8811
telemt_desync_full_logged_total 2800
telemt_desync_suppressed_total 6011
telemt_desync_frames_bucket_total{bucket="1_2"} 1611
telemt_desync_frames_bucket_total{bucket="3_10"} 3089
telemt_desync_frames_bucket_total{bucket="gt_10"} 4111
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4449
telemt_me_writer_restored_same_endpoint_total 4358
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1649411
telemt_user_connections_current{user="hello"} 1233
telemt_user_octets_from_client{user="hello"} 28043061672 (26.12 GB)
telemt_user_octets_to_client{user="hello"} 832473820936 (775.30 GB)
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 114
```