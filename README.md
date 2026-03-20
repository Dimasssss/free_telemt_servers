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

# Server Metrics 2026-03-20 00:58:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 27648.9 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530011
telemt_connections_bad_total 34383
telemt_connections_current 734
telemt_connections_me_current 734
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7629
telemt_upstream_connect_attempt_total 5920
telemt_upstream_connect_success_total 5841
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 5920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3372
telemt_me_reconnect_success_total 3338
telemt_me_reader_eof_total 3515
telemt_me_idle_close_by_peer_total 3514
telemt_me_route_drop_no_conn_total 154967
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422192
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2049
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 417
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3357
telemt_me_writer_restored_same_endpoint_total 3325
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 423622
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 29487257860 (27.46 GB)
telemt_user_octets_to_client{user="hello"} 153243514301 (142.72 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 44103.3 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2960505
telemt_connections_bad_total 125466
telemt_connections_current 1283
telemt_connections_me_current 1283
telemt_handshake_timeouts_total 64204
telemt_upstream_connect_attempt_total 8788
telemt_upstream_connect_success_total 8644
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 8788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9469
telemt_me_reconnect_success_total 5230
telemt_me_reader_eof_total 5600
telemt_me_idle_close_by_peer_total 5600
telemt_me_route_drop_no_conn_total 1492181
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2534541
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10962
telemt_desync_full_logged_total 3605
telemt_desync_suppressed_total 7357
telemt_desync_frames_bucket_total{bucket="1_2"} 2089
telemt_desync_frames_bucket_total{bucket="3_10"} 4292
telemt_desync_frames_bucket_total{bucket="gt_10"} 4581
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5419
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5175
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 2534323
telemt_user_connections_current{user="hello"} 1283
telemt_user_octets_from_client{user="hello"} 38990702782 (36.31 GB)
telemt_user_octets_to_client{user="hello"} 924156003594 (860.69 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 607
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 44081.3 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2898656
telemt_connections_bad_total 470233
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_handshake_timeouts_total 41495
telemt_upstream_connect_attempt_total 7036
telemt_upstream_connect_success_total 6984
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 7036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5730
telemt_me_reconnect_success_total 4797
telemt_me_reader_eof_total 5023
telemt_me_idle_close_by_peer_total 5022
telemt_me_route_drop_no_conn_total 1908303
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2004954
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7600
telemt_desync_full_logged_total 2303
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1870
telemt_desync_frames_bucket_total{bucket="3_10"} 2899
telemt_desync_frames_bucket_total{bucket="gt_10"} 2831
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 4844
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4796
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 2000627
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 29696048404 (27.66 GB)
telemt_user_octets_to_client{user="hello"} 762855082352 (710.46 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 44072.3 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2513696
telemt_connections_bad_total 112484
telemt_connections_current 533
telemt_connections_direct_current 533
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30534
telemt_upstream_connect_attempt_total 54878
telemt_upstream_connect_success_total 50609
telemt_upstream_connect_fail_total 4225
telemt_upstream_connect_attempts_per_request{bucket="1"} 54834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4225
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8137
telemt_me_reconnect_success_total 5312
telemt_me_reader_eof_total 5508
telemt_me_idle_close_by_peer_total 5507
telemt_me_route_drop_no_conn_total 1857220
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2108852
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8257
telemt_desync_full_logged_total 2605
telemt_desync_suppressed_total 5652
telemt_desync_frames_bucket_total{bucket="1_2"} 2026
telemt_desync_frames_bucket_total{bucket="3_10"} 3004
telemt_desync_frames_bucket_total{bucket="gt_10"} 3227
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 5928
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5308
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 2150786
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 35278604663 (32.86 GB)
telemt_user_octets_to_client{user="hello"} 602754015384 (561.36 GB)
telemt_user_msgs_from_client{user="hello"} 240582
telemt_user_msgs_to_client{user="hello"} 1741125
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 97792.6 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6231968
telemt_connections_bad_total 1039986
telemt_connections_current 1164
telemt_connections_me_current 1164
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 112355
telemt_upstream_connect_attempt_total 127019
telemt_upstream_connect_success_total 93736
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78210
telemt_me_reconnect_success_total 12540
telemt_me_reader_eof_total 13510
telemt_me_idle_close_by_peer_total 13496
telemt_me_route_drop_no_conn_total 2786002
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4411299
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
telemt_desync_total 19407
telemt_desync_full_logged_total 6135
telemt_desync_suppressed_total 13272
telemt_desync_frames_bucket_total{bucket="1_2"} 3404
telemt_desync_frames_bucket_total{bucket="3_10"} 7976
telemt_desync_frames_bucket_total{bucket="gt_10"} 8027
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 12844
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12515
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4486513
telemt_user_connections_current{user="hello"} 1164
telemt_user_octets_from_client{user="hello"} 70211157976 (65.39 GB)
telemt_user_octets_to_client{user="hello"} 1730875992352 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 519
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 44032.5 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697569
telemt_connections_bad_total 72463
telemt_connections_current 364
telemt_connections_me_current 364
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12969
telemt_upstream_connect_attempt_total 13106
telemt_upstream_connect_success_total 12776
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6244
telemt_me_reconnect_success_total 6138
telemt_me_reader_eof_total 6430
telemt_me_idle_close_by_peer_total 6427
telemt_me_route_drop_no_conn_total 465117
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574135
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6195
telemt_me_writer_restored_same_endpoint_total 6129
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 562280
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 7230498071 (6.73 GB)
telemt_user_octets_to_client{user="hello"} 139998706474 (130.38 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 44033.9 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1993246
telemt_connections_bad_total 119578
telemt_connections_current 1084
telemt_connections_me_current 1084
telemt_handshake_timeouts_total 36856
telemt_upstream_connect_attempt_total 7761
telemt_upstream_connect_success_total 7705
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5550
telemt_me_reconnect_success_total 5510
telemt_me_reader_eof_total 5812
telemt_me_idle_close_by_peer_total 5812
telemt_me_route_drop_no_conn_total 735575
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1717512
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9079
telemt_desync_full_logged_total 2914
telemt_desync_suppressed_total 6165
telemt_desync_frames_bucket_total{bucket="1_2"} 1686
telemt_desync_frames_bucket_total{bucket="3_10"} 3197
telemt_desync_frames_bucket_total{bucket="gt_10"} 4196
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5595
telemt_me_writer_restored_same_endpoint_total 5493
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1716628
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 29458813356 (27.44 GB)
telemt_user_octets_to_client{user="hello"} 869529789016 (809.81 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 75
```