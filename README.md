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

# Server Metrics 2026-03-19 19:39:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 8488.7 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261119
telemt_connections_bad_total 11416
telemt_connections_current 1256
telemt_connections_me_current 1256
telemt_handshake_timeouts_total 2660
telemt_upstream_connect_attempt_total 1300
telemt_upstream_connect_success_total 1285
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 830
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 77808
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203571
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1000
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 672
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 846
telemt_me_writer_restored_same_endpoint_total 811
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 203815
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 8318752356 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 71767445744 (66.84 GB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 24944.2 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2357180
telemt_connections_bad_total 105233
telemt_connections_current 3423
telemt_connections_me_current 3423
telemt_handshake_timeouts_total 45056
telemt_upstream_connect_attempt_total 5349
telemt_upstream_connect_success_total 5277
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7006
telemt_me_reconnect_success_total 2779
telemt_me_reader_eof_total 3002
telemt_me_idle_close_by_peer_total 3002
telemt_me_route_drop_no_conn_total 1287655
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1988290
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8327
telemt_desync_full_logged_total 2706
telemt_desync_suppressed_total 5621
telemt_desync_frames_bucket_total{bucket="1_2"} 1526
telemt_desync_frames_bucket_total{bucket="3_10"} 3291
telemt_desync_frames_bucket_total{bucket="gt_10"} 3510
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2935
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2724
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 1988284
telemt_user_connections_current{user="hello"} 3423
telemt_user_octets_from_client{user="hello"} 29095258834 (27.10 GB)
telemt_user_octets_to_client{user="hello"} 674669921162 (628.34 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1201
telemt_user_unique_ips_recent_window{user="hello"} 427
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 24922.4 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2131982
telemt_connections_bad_total 252275
telemt_connections_current 2727
telemt_connections_me_current 2727
telemt_handshake_timeouts_total 24939
telemt_upstream_connect_attempt_total 3868
telemt_upstream_connect_success_total 3842
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3491
telemt_me_reconnect_success_total 2572
telemt_me_reader_eof_total 2645
telemt_me_idle_close_by_peer_total 2644
telemt_me_route_drop_no_conn_total 1756335
telemt_me_route_drop_channel_closed_total 156
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1622514
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5765
telemt_desync_full_logged_total 1725
telemt_desync_suppressed_total 4040
telemt_desync_frames_bucket_total{bucket="1_2"} 1460
telemt_desync_frames_bucket_total{bucket="3_10"} 2180
telemt_desync_frames_bucket_total{bucket="gt_10"} 2125
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 2573
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2571
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1618869
telemt_user_connections_current{user="hello"} 2727
telemt_user_octets_from_client{user="hello"} 22950924308 (21.37 GB)
telemt_user_octets_to_client{user="hello"} 551046258548 (513.20 GB)
telemt_user_unique_ips_current{user="hello"} 872
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 24910.0 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2013230
telemt_connections_bad_total 66776
telemt_connections_current 2266
telemt_connections_me_current 2266
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 25778
telemt_upstream_connect_attempt_total 31105
telemt_upstream_connect_success_total 29581
telemt_upstream_connect_fail_total 1524
telemt_upstream_connect_attempts_per_request{bucket="1"} 31105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1524
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5539
telemt_me_reconnect_success_total 3012
telemt_me_reader_eof_total 3117
telemt_me_idle_close_by_peer_total 3116
telemt_me_route_drop_no_conn_total 1701570
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1730371
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7013
telemt_desync_full_logged_total 2194
telemt_desync_suppressed_total 4819
telemt_desync_frames_bucket_total{bucket="1_2"} 1732
telemt_desync_frames_bucket_total{bucket="3_10"} 2576
telemt_desync_frames_bucket_total{bucket="gt_10"} 2705
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 288
telemt_me_writer_removed_unexpected_total 3460
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3008
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 1754559
telemt_user_connections_current{user="hello"} 2266
telemt_user_octets_from_client{user="hello"} 30023006388 (27.96 GB)
telemt_user_octets_to_client{user="hello"} 398939346170 (371.54 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 78633.2 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5689138
telemt_connections_bad_total 1016244
telemt_connections_current 2688
telemt_connections_me_current 2688
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 103992
telemt_upstream_connect_attempt_total 65466
telemt_upstream_connect_success_total 62968
telemt_upstream_connect_fail_total 2498
telemt_upstream_connect_attempts_per_request{bucket="1"} 65466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75257
telemt_me_reconnect_success_total 9844
telemt_me_reader_eof_total 10384
telemt_me_idle_close_by_peer_total 10381
telemt_me_route_drop_no_conn_total 2615109
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3982829
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
telemt_desync_total 17522
telemt_desync_full_logged_total 5404
telemt_desync_suppressed_total 12118
telemt_desync_frames_bucket_total{bucket="1_2"} 2925
telemt_desync_frames_bucket_total{bucket="3_10"} 7287
telemt_desync_frames_bucket_total{bucket="gt_10"} 7310
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 10097
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9820
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 4030904
telemt_user_connections_current{user="hello"} 2688
telemt_user_octets_from_client{user="hello"} 62825205691 (58.51 GB)
telemt_user_octets_to_client{user="hello"} 1505499887360 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 995
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 24873.4 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551282
telemt_connections_bad_total 42570
telemt_connections_current 559
telemt_connections_me_current 559
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10814
telemt_upstream_connect_attempt_total 7701
telemt_upstream_connect_success_total 7504
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3301
telemt_me_reconnect_success_total 3243
telemt_me_reader_eof_total 3344
telemt_me_idle_close_by_peer_total 3343
telemt_me_route_drop_no_conn_total 376035
telemt_me_route_drop_channel_closed_total 133
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436606
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
telemt_desync_total 1124
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 136
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3268
telemt_me_writer_restored_same_endpoint_total 3234
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 455247
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 5184535912 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 96383017266 (89.76 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 24874.5 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1582857
telemt_connections_bad_total 96588
telemt_connections_current 2789
telemt_connections_me_current 2789
telemt_handshake_timeouts_total 25783
telemt_upstream_connect_attempt_total 4106
telemt_upstream_connect_success_total 4076
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2829
telemt_me_reconnect_success_total 2800
telemt_me_reader_eof_total 2939
telemt_me_idle_close_by_peer_total 2939
telemt_me_route_drop_no_conn_total 602019
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373545
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7221
telemt_desync_full_logged_total 2233
telemt_desync_suppressed_total 4988
telemt_desync_frames_bucket_total{bucket="1_2"} 1360
telemt_desync_frames_bucket_total{bucket="3_10"} 2511
telemt_desync_frames_bucket_total{bucket="gt_10"} 3350
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2857
telemt_me_writer_restored_same_endpoint_total 2783
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1372798
telemt_user_connections_current{user="hello"} 2789
telemt_user_octets_from_client{user="hello"} 22264844368 (20.74 GB)
telemt_user_octets_to_client{user="hello"} 634476135012 (590.90 GB)
telemt_user_unique_ips_current{user="hello"} 897
telemt_user_unique_ips_recent_window{user="hello"} 318
```