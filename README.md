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

# Server Metrics 2026-03-19 22:20:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 18159.0 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415547
telemt_connections_bad_total 22843
telemt_connections_current 764
telemt_connections_me_current 764
telemt_handshake_timeouts_total 6012
telemt_upstream_connect_attempt_total 3009
telemt_upstream_connect_success_total 2981
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2054
telemt_me_reconnect_success_total 2038
telemt_me_reader_eof_total 2160
telemt_me_idle_close_by_peer_total 2160
telemt_me_route_drop_no_conn_total 124762
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330152
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1792
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1168
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 845
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 2082
telemt_me_writer_restored_same_endpoint_total 2025
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 330430
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 11549602436 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 122854724360 (114.42 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 34614.3 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2770616
telemt_connections_bad_total 119700
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_handshake_timeouts_total 55174
telemt_upstream_connect_attempt_total 7064
telemt_upstream_connect_success_total 6953
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 7064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8206
telemt_me_reconnect_success_total 3975
telemt_me_reader_eof_total 4268
telemt_me_idle_close_by_peer_total 4268
telemt_me_route_drop_no_conn_total 1439521
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2364654
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10488
telemt_desync_full_logged_total 3422
telemt_desync_suppressed_total 7066
telemt_desync_frames_bucket_total{bucket="1_2"} 1951
telemt_desync_frames_bucket_total{bucket="3_10"} 4096
telemt_desync_frames_bucket_total{bucket="gt_10"} 4441
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 4144
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3920
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 2364531
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 37464948010 (34.89 GB)
telemt_user_octets_to_client{user="hello"} 846341374286 (788.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 725
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 34592.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2697457
telemt_connections_bad_total 459517
telemt_connections_current 1282
telemt_connections_me_current 1282
telemt_handshake_timeouts_total 34507
telemt_upstream_connect_attempt_total 5428
telemt_upstream_connect_success_total 5384
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 5428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4561
telemt_me_reconnect_success_total 3633
telemt_me_reader_eof_total 3780
telemt_me_idle_close_by_peer_total 3779
telemt_me_route_drop_no_conn_total 1861473
telemt_me_route_drop_channel_closed_total 167
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1883291
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7341
telemt_desync_full_logged_total 2208
telemt_desync_suppressed_total 5133
telemt_desync_frames_bucket_total{bucket="1_2"} 1810
telemt_desync_frames_bucket_total{bucket="3_10"} 2808
telemt_desync_frames_bucket_total{bucket="gt_10"} 2723
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 61
telemt_me_writer_removed_unexpected_total 3658
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3632
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1879216
telemt_user_connections_current{user="hello"} 1282
telemt_user_octets_from_client{user="hello"} 28456021016 (26.50 GB)
telemt_user_octets_to_client{user="hello"} 693585590064 (645.95 GB)
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 34580.3 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2364302
telemt_connections_bad_total 99249
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29408
telemt_upstream_connect_attempt_total 35799
telemt_upstream_connect_success_total 34058
telemt_upstream_connect_fail_total 1741
telemt_upstream_connect_attempts_per_request{bucket="1"} 35799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1741
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6853
telemt_me_reconnect_success_total 4228
telemt_me_reader_eof_total 4387
telemt_me_idle_close_by_peer_total 4386
telemt_me_route_drop_no_conn_total 1823652
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2007328
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8066
telemt_desync_full_logged_total 2528
telemt_desync_suppressed_total 5538
telemt_desync_frames_bucket_total{bucket="1_2"} 1978
telemt_desync_frames_bucket_total{bucket="3_10"} 2930
telemt_desync_frames_bucket_total{bucket="gt_10"} 3158
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4750
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4224
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2034259
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 33386283660 (31.09 GB)
telemt_user_octets_to_client{user="hello"} 528152852199 (491.88 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 88303.5 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6036412
telemt_connections_bad_total 1036340
telemt_connections_current 1631
telemt_connections_me_current 1631
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109234
telemt_upstream_connect_attempt_total 67044
telemt_upstream_connect_success_total 64537
telemt_upstream_connect_fail_total 2507
telemt_upstream_connect_attempts_per_request{bucket="1"} 67044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2507
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76351
telemt_me_reconnect_success_total 10932
telemt_me_reader_eof_total 11539
telemt_me_idle_close_by_peer_total 11536
telemt_me_route_drop_no_conn_total 2748235
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4287028
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
telemt_desync_total 18903
telemt_desync_full_logged_total 5872
telemt_desync_suppressed_total 13031
telemt_desync_frames_bucket_total{bucket="1_2"} 3303
telemt_desync_frames_bucket_total{bucket="3_10"} 7768
telemt_desync_frames_bucket_total{bucket="gt_10"} 7832
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 11197
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10908
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 4335077
telemt_user_connections_current{user="hello"} 1631
telemt_user_octets_from_client{user="hello"} 67141916019 (62.53 GB)
telemt_user_octets_to_client{user="hello"} 1677923858976 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 34543.6 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631936
telemt_connections_bad_total 50000
telemt_connections_current 394
telemt_connections_me_current 394
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12084
telemt_upstream_connect_attempt_total 9536
telemt_upstream_connect_success_total 9323
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4660
telemt_me_reconnect_success_total 4581
telemt_me_reader_eof_total 4778
telemt_me_idle_close_by_peer_total 4776
telemt_me_route_drop_no_conn_total 447375
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536042
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
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 146
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4622
telemt_me_writer_restored_same_endpoint_total 4572
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 522709
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 6887043836 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 124975149162 (116.39 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 34545.0 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1869217
telemt_connections_bad_total 108955
telemt_connections_current 1419
telemt_connections_me_current 1419
telemt_handshake_timeouts_total 34493
telemt_upstream_connect_attempt_total 5819
telemt_upstream_connect_success_total 5775
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 5819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4051
telemt_me_reconnect_success_total 4016
telemt_me_reader_eof_total 4228
telemt_me_idle_close_by_peer_total 4228
telemt_me_route_drop_no_conn_total 699150
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1620745
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8661
telemt_desync_full_logged_total 2736
telemt_desync_suppressed_total 5925
telemt_desync_frames_bucket_total{bucket="1_2"} 1590
telemt_desync_frames_bucket_total{bucket="3_10"} 3019
telemt_desync_frames_bucket_total{bucket="gt_10"} 4052
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4088
telemt_me_writer_restored_same_endpoint_total 3999
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1619889
telemt_user_connections_current{user="hello"} 1419
telemt_user_octets_from_client{user="hello"} 27600097472 (25.70 GB)
telemt_user_octets_to_client{user="hello"} 810658931012 (754.98 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 113
```