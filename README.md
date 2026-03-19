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

# Server Metrics 2026-03-19 19:08:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 6652.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216337
telemt_connections_bad_total 8288
telemt_connections_current 1243
telemt_connections_me_current 1243
telemt_handshake_timeouts_total 2213
telemt_upstream_connect_attempt_total 1002
telemt_upstream_connect_success_total 988
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 634
telemt_me_idle_close_by_peer_total 634
telemt_me_route_drop_no_conn_total 65864
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167243
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 761
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_restored_same_endpoint_total 603
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 167448
telemt_user_connections_current{user="hello"} 1243
telemt_user_octets_from_client{user="hello"} 2611713588 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 57285882124 (53.35 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 23108.2 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2231159
telemt_connections_bad_total 102116
telemt_connections_current 3622
telemt_connections_me_current 3622
telemt_handshake_timeouts_total 42135
telemt_upstream_connect_attempt_total 5098
telemt_upstream_connect_success_total 5032
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 5098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6847
telemt_me_reconnect_success_total 2621
telemt_me_reader_eof_total 2829
telemt_me_idle_close_by_peer_total 2829
telemt_me_route_drop_no_conn_total 1239014
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1873615
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7670
telemt_desync_full_logged_total 2464
telemt_desync_suppressed_total 5206
telemt_desync_frames_bucket_total{bucket="1_2"} 1434
telemt_desync_frames_bucket_total{bucket="3_10"} 3035
telemt_desync_frames_bucket_total{bucket="gt_10"} 3201
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2770
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2566
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 1873589
telemt_user_connections_current{user="hello"} 3622
telemt_user_octets_from_client{user="hello"} 27428546698 (25.54 GB)
telemt_user_octets_to_client{user="hello"} 623798866326 (580.96 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 23086.3 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2028568
telemt_connections_bad_total 242147
telemt_connections_current 2715
telemt_connections_me_current 2715
telemt_handshake_timeouts_total 23577
telemt_upstream_connect_attempt_total 3611
telemt_upstream_connect_success_total 3586
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3322
telemt_me_reconnect_success_total 2404
telemt_me_reader_eof_total 2464
telemt_me_idle_close_by_peer_total 2463
telemt_me_route_drop_no_conn_total 1725726
telemt_me_route_drop_channel_closed_total 148
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1544040
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5337
telemt_desync_full_logged_total 1586
telemt_desync_suppressed_total 3751
telemt_desync_frames_bucket_total{bucket="1_2"} 1351
telemt_desync_frames_bucket_total{bucket="3_10"} 2018
telemt_desync_frames_bucket_total{bucket="gt_10"} 1968
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 2402
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2403
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1540401
telemt_user_connections_current{user="hello"} 2715
telemt_user_octets_from_client{user="hello"} 20547650448 (19.14 GB)
telemt_user_octets_to_client{user="hello"} 510321698204 (475.27 GB)
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 23074.1 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1901780
telemt_connections_bad_total 63302
telemt_connections_current 2630
telemt_connections_me_current 2630
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24747
telemt_upstream_connect_attempt_total 25656
telemt_upstream_connect_success_total 24456
telemt_upstream_connect_fail_total 1199
telemt_upstream_connect_attempts_per_request{bucket="1"} 25655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1199
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5235
telemt_me_reconnect_success_total 2848
telemt_me_reader_eof_total 2954
telemt_me_idle_close_by_peer_total 2953
telemt_me_route_drop_no_conn_total 1643632
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1641086
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6500
telemt_desync_full_logged_total 2013
telemt_desync_suppressed_total 4487
telemt_desync_frames_bucket_total{bucket="1_2"} 1661
telemt_desync_frames_bucket_total{bucket="3_10"} 2379
telemt_desync_frames_bucket_total{bucket="gt_10"} 2460
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3265
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2844
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 1660415
telemt_user_connections_current{user="hello"} 2630
telemt_user_octets_from_client{user="hello"} 28152057341 (26.22 GB)
telemt_user_octets_to_client{user="hello"} 371425196685 (345.92 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 908
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 76797.3 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5588841
telemt_connections_bad_total 1010558
telemt_connections_current 2944
telemt_connections_me_current 2944
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 101990
telemt_upstream_connect_attempt_total 65221
telemt_upstream_connect_success_total 62725
telemt_upstream_connect_fail_total 2496
telemt_upstream_connect_attempts_per_request{bucket="1"} 65221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2496
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75100
telemt_me_reconnect_success_total 9690
telemt_me_reader_eof_total 10220
telemt_me_idle_close_by_peer_total 10217
telemt_me_route_drop_no_conn_total 2561961
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3898123
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
telemt_desync_total 17191
telemt_desync_full_logged_total 5268
telemt_desync_suppressed_total 11923
telemt_desync_frames_bucket_total{bucket="1_2"} 2874
telemt_desync_frames_bucket_total{bucket="3_10"} 7128
telemt_desync_frames_bucket_total{bucket="gt_10"} 7189
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 9939
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9666
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 3946242
telemt_user_connections_current{user="hello"} 2944
telemt_user_octets_from_client{user="hello"} 61691115027 (57.45 GB)
telemt_user_octets_to_client{user="hello"} 1458802439508 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 23038.5 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525242
telemt_connections_bad_total 38374
telemt_connections_current 626
telemt_connections_me_current 626
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10618
telemt_upstream_connect_attempt_total 7411
telemt_upstream_connect_success_total 7214
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3098
telemt_me_reconnect_success_total 3041
telemt_me_reader_eof_total 3128
telemt_me_idle_close_by_peer_total 3127
telemt_me_route_drop_no_conn_total 366578
telemt_me_route_drop_channel_closed_total 130
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415816
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
telemt_desync_total 1096
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 15
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 134
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3063
telemt_me_writer_restored_same_endpoint_total 3032
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 434459
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 4930431156 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 90979794386 (84.73 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 23038.8 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1490414
telemt_connections_bad_total 90340
telemt_connections_current 3127
telemt_connections_me_current 3127
telemt_handshake_timeouts_total 25240
telemt_upstream_connect_attempt_total 3793
telemt_upstream_connect_success_total 3765
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2604
telemt_me_reconnect_success_total 2576
telemt_me_reader_eof_total 2704
telemt_me_idle_close_by_peer_total 2704
telemt_me_route_drop_no_conn_total 572447
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1293263
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6836
telemt_desync_full_logged_total 2113
telemt_desync_suppressed_total 4723
telemt_desync_frames_bucket_total{bucket="1_2"} 1285
telemt_desync_frames_bucket_total{bucket="3_10"} 2388
telemt_desync_frames_bucket_total{bucket="gt_10"} 3163
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2630
telemt_me_writer_restored_same_endpoint_total 2559
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 1292512
telemt_user_connections_current{user="hello"} 3127
telemt_user_octets_from_client{user="hello"} 20641365852 (19.22 GB)
telemt_user_octets_to_client{user="hello"} 579482975844 (539.69 GB)
telemt_user_unique_ips_current{user="hello"} 956
telemt_user_unique_ips_recent_window{user="hello"} 371
```