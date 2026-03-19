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

# Server Metrics 2026-03-19 22:10:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 17547.2 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407129
telemt_connections_bad_total 21037
telemt_connections_current 841
telemt_connections_me_current 841
telemt_handshake_timeouts_total 5919
telemt_upstream_connect_attempt_total 2889
telemt_upstream_connect_success_total 2862
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1978
telemt_me_reconnect_success_total 1963
telemt_me_reader_eof_total 2077
telemt_me_idle_close_by_peer_total 2077
telemt_me_route_drop_no_conn_total 123059
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323985
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1759
telemt_desync_full_logged_total 610
telemt_desync_suppressed_total 1149
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 2006
telemt_me_writer_restored_same_endpoint_total 1950
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 324263
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 11473042356 (10.69 GB)
telemt_user_octets_to_client{user="hello"} 120894734704 (112.59 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 34002.7 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755037
telemt_connections_bad_total 118796
telemt_connections_current 1696
telemt_connections_me_current 1696
telemt_handshake_timeouts_total 54620
telemt_upstream_connect_attempt_total 6924
telemt_upstream_connect_success_total 6815
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 6924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8113
telemt_me_reconnect_success_total 3883
telemt_me_reader_eof_total 4170
telemt_me_idle_close_by_peer_total 4170
telemt_me_route_drop_no_conn_total 1434870
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2350891
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10430
telemt_desync_full_logged_total 3395
telemt_desync_suppressed_total 7035
telemt_desync_frames_bucket_total{bucket="1_2"} 1941
telemt_desync_frames_bucket_total{bucket="3_10"} 4069
telemt_desync_frames_bucket_total{bucket="gt_10"} 4420
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 4052
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3828
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 2350768
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 37351298362 (34.79 GB)
telemt_user_octets_to_client{user="hello"} 839480447078 (781.83 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 33980.9 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2682995
telemt_connections_bad_total 458378
telemt_connections_current 1331
telemt_connections_me_current 1331
telemt_handshake_timeouts_total 34156
telemt_upstream_connect_attempt_total 5301
telemt_upstream_connect_success_total 5259
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 5301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4479
telemt_me_reconnect_success_total 3552
telemt_me_reader_eof_total 3693
telemt_me_idle_close_by_peer_total 3692
telemt_me_route_drop_no_conn_total 1857952
telemt_me_route_drop_channel_closed_total 166
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1874260
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7304
telemt_desync_full_logged_total 2194
telemt_desync_suppressed_total 5110
telemt_desync_frames_bucket_total{bucket="1_2"} 1801
telemt_desync_frames_bucket_total{bucket="3_10"} 2791
telemt_desync_frames_bucket_total{bucket="gt_10"} 2712
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 61
telemt_me_writer_removed_unexpected_total 3575
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3551
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1870185
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 28371196412 (26.42 GB)
telemt_user_octets_to_client{user="hello"} 688076967792 (640.82 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 33968.7 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2353242
telemt_connections_bad_total 99136
telemt_connections_current 1337
telemt_connections_me_current 1337
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29324
telemt_upstream_connect_attempt_total 35638
telemt_upstream_connect_success_total 33903
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 35638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6737
telemt_me_reconnect_success_total 4116
telemt_me_reader_eof_total 4260
telemt_me_idle_close_by_peer_total 4259
telemt_me_route_drop_no_conn_total 1820460
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1998021
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8031
telemt_desync_full_logged_total 2508
telemt_desync_suppressed_total 5523
telemt_desync_frames_bucket_total{bucket="1_2"} 1976
telemt_desync_frames_bucket_total{bucket="3_10"} 2912
telemt_desync_frames_bucket_total{bucket="gt_10"} 3143
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4636
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4112
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 2024952
telemt_user_connections_current{user="hello"} 1337
telemt_user_octets_from_client{user="hello"} 33295070364 (31.01 GB)
telemt_user_octets_to_client{user="hello"} 524859198499 (488.81 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 87691.9 (24h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6023456
telemt_connections_bad_total 1036077
telemt_connections_current 1632
telemt_connections_me_current 1632
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108938
telemt_upstream_connect_attempt_total 66928
telemt_upstream_connect_success_total 64422
telemt_upstream_connect_fail_total 2506
telemt_upstream_connect_attempts_per_request{bucket="1"} 66928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2506
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76279
telemt_me_reconnect_success_total 10861
telemt_me_reader_eof_total 11467
telemt_me_idle_close_by_peer_total 11464
telemt_me_route_drop_no_conn_total 2744120
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4275274
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
telemt_desync_total 18843
telemt_desync_full_logged_total 5853
telemt_desync_suppressed_total 12990
telemt_desync_frames_bucket_total{bucket="1_2"} 3286
telemt_desync_frames_bucket_total{bucket="3_10"} 7749
telemt_desync_frames_bucket_total{bucket="gt_10"} 7808
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 11125
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10837
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 4323324
telemt_user_connections_current{user="hello"} 1632
telemt_user_octets_from_client{user="hello"} 67002024299 (62.40 GB)
telemt_user_octets_to_client{user="hello"} 1671518005772 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 33931.8 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627963
telemt_connections_bad_total 49743
telemt_connections_current 379
telemt_connections_me_current 379
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11964
telemt_upstream_connect_attempt_total 9394
telemt_upstream_connect_success_total 9181
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4562
telemt_me_reconnect_success_total 4483
telemt_me_reader_eof_total 4670
telemt_me_idle_close_by_peer_total 4668
telemt_me_route_drop_no_conn_total 439380
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526984
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
telemt_desync_total 1353
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4524
telemt_me_writer_restored_same_endpoint_total 4474
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 519385
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 6840755320 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 122823300850 (114.39 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 33933.2 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1860558
telemt_connections_bad_total 108826
telemt_connections_current 1489
telemt_connections_me_current 1489
telemt_handshake_timeouts_total 34106
telemt_upstream_connect_attempt_total 5680
telemt_upstream_connect_success_total 5639
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3958
telemt_me_reconnect_success_total 3923
telemt_me_reader_eof_total 4131
telemt_me_idle_close_by_peer_total 4131
telemt_me_route_drop_no_conn_total 695549
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1612740
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8637
telemt_desync_full_logged_total 2718
telemt_desync_suppressed_total 5919
telemt_desync_frames_bucket_total{bucket="1_2"} 1583
telemt_desync_frames_bucket_total{bucket="3_10"} 3013
telemt_desync_frames_bucket_total{bucket="gt_10"} 4041
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 3995
telemt_me_writer_restored_same_endpoint_total 3906
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1611884
telemt_user_connections_current{user="hello"} 1489
telemt_user_octets_from_client{user="hello"} 27503721696 (25.61 GB)
telemt_user_octets_to_client{user="hello"} 805269735520 (749.97 GB)
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 128
```