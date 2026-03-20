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

# Server Metrics 2026-03-20 01:13:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 28568.9 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542910
telemt_connections_bad_total 35209
telemt_connections_current 808
telemt_connections_me_current 808
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7807
telemt_upstream_connect_attempt_total 6100
telemt_upstream_connect_success_total 6019
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 6100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3507
telemt_me_reconnect_success_total 3471
telemt_me_reader_eof_total 3655
telemt_me_idle_close_by_peer_total 3654
telemt_me_route_drop_no_conn_total 158591
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433196
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2078
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1332
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3493
telemt_me_writer_restored_same_endpoint_total 3458
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 434626
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 29580923704 (27.55 GB)
telemt_user_octets_to_client{user="hello"} 156405775589 (145.66 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 45024.2 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2975540
telemt_connections_bad_total 125794
telemt_connections_current 1326
telemt_connections_me_current 1326
telemt_handshake_timeouts_total 64682
telemt_upstream_connect_attempt_total 8950
telemt_upstream_connect_success_total 8804
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 8950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9586
telemt_me_reconnect_success_total 5347
telemt_me_reader_eof_total 5722
telemt_me_idle_close_by_peer_total 5722
telemt_me_route_drop_no_conn_total 1496166
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2548469
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11031
telemt_desync_full_logged_total 3623
telemt_desync_suppressed_total 7408
telemt_desync_frames_bucket_total{bucket="1_2"} 2111
telemt_desync_frames_bucket_total{bucket="3_10"} 4315
telemt_desync_frames_bucket_total{bucket="gt_10"} 4605
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5538
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5292
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 2548251
telemt_user_connections_current{user="hello"} 1326
telemt_user_octets_from_client{user="hello"} 39118714462 (36.43 GB)
telemt_user_octets_to_client{user="hello"} 929368296418 (865.54 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 45002.4 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2919881
telemt_connections_bad_total 472260
telemt_connections_current 1083
telemt_connections_me_current 1083
telemt_handshake_timeouts_total 42251
telemt_upstream_connect_attempt_total 7203
telemt_upstream_connect_success_total 7151
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 7203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5851
telemt_me_reconnect_success_total 4918
telemt_me_reader_eof_total 5154
telemt_me_idle_close_by_peer_total 5153
telemt_me_route_drop_no_conn_total 1913518
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2016647
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7610
telemt_desync_full_logged_total 2306
telemt_desync_suppressed_total 5304
telemt_desync_frames_bucket_total{bucket="1_2"} 1876
telemt_desync_frames_bucket_total{bucket="3_10"} 2901
telemt_desync_frames_bucket_total{bucket="gt_10"} 2833
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 4966
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4917
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2012307
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 29790467124 (27.74 GB)
telemt_user_octets_to_client{user="hello"} 767365586188 (714.66 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 44990.4 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2535365
telemt_connections_bad_total 118566
telemt_connections_current 1036
telemt_connections_me_current 1036
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30995
telemt_upstream_connect_attempt_total 55151
telemt_upstream_connect_success_total 50888
telemt_upstream_connect_fail_total 4263
telemt_upstream_connect_attempts_per_request{bucket="1"} 55151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4263
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8240
telemt_me_reconnect_success_total 5411
telemt_me_reader_eof_total 5612
telemt_me_idle_close_by_peer_total 5611
telemt_me_route_drop_no_conn_total 1859631
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2121231
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8276
telemt_desync_full_logged_total 2614
telemt_desync_suppressed_total 5662
telemt_desync_frames_bucket_total{bucket="1_2"} 2030
telemt_desync_frames_bucket_total{bucket="3_10"} 3014
telemt_desync_frames_bucket_total{bucket="gt_10"} 3232
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6030
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5407
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 2163302
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 35395658537 (32.96 GB)
telemt_user_octets_to_client{user="hello"} 605681902393 (564.09 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 98713.7 (27h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6246154
telemt_connections_bad_total 1040972
telemt_connections_current 1239
telemt_connections_me_current 1239
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 112692
telemt_upstream_connect_attempt_total 127185
telemt_upstream_connect_success_total 93902
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78333
telemt_me_reconnect_success_total 12663
telemt_me_reader_eof_total 13642
telemt_me_idle_close_by_peer_total 13628
telemt_me_route_drop_no_conn_total 2790617
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4423739
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
telemt_desync_total 19460
telemt_desync_full_logged_total 6157
telemt_desync_suppressed_total 13303
telemt_desync_frames_bucket_total{bucket="1_2"} 3419
telemt_desync_frames_bucket_total{bucket="3_10"} 8006
telemt_desync_frames_bucket_total{bucket="gt_10"} 8035
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 12969
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12638
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 4498953
telemt_user_connections_current{user="hello"} 1239
telemt_user_octets_from_client{user="hello"} 70710427016 (65.85 GB)
telemt_user_octets_to_client{user="hello"} 1734193149952 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 44953.6 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703248
telemt_connections_bad_total 74383
telemt_connections_current 349
telemt_connections_me_current 349
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12989
telemt_upstream_connect_attempt_total 13312
telemt_upstream_connect_success_total 12982
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6407
telemt_me_reconnect_success_total 6300
telemt_me_reader_eof_total 6602
telemt_me_idle_close_by_peer_total 6599
telemt_me_route_drop_no_conn_total 466799
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577794
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
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6359
telemt_me_writer_restored_same_endpoint_total 6291
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 565939
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 7290528115 (6.79 GB)
telemt_user_octets_to_client{user="hello"} 142178500582 (132.41 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 44954.9 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2002752
telemt_connections_bad_total 119959
telemt_connections_current 1138
telemt_connections_me_current 1138
telemt_handshake_timeouts_total 37091
telemt_upstream_connect_attempt_total 7963
telemt_upstream_connect_success_total 7904
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 7963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5706
telemt_me_reconnect_success_total 5665
telemt_me_reader_eof_total 5976
telemt_me_idle_close_by_peer_total 5976
telemt_me_route_drop_no_conn_total 738446
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1726060
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9136
telemt_desync_full_logged_total 2935
telemt_desync_suppressed_total 6201
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 3210
telemt_desync_frames_bucket_total{bucket="gt_10"} 4224
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 5751
telemt_me_writer_restored_same_endpoint_total 5648
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 1725169
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 29526744908 (27.50 GB)
telemt_user_octets_to_client{user="hello"} 872813145828 (812.87 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 77
```