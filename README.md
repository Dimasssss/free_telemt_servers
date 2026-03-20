# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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

# Server Metrics 2026-03-20 07:15:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 50286.0 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1045558
telemt_connections_bad_total 62647
telemt_connections_current 1786
telemt_connections_me_current 1786
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27112
telemt_upstream_connect_attempt_total 9718
telemt_upstream_connect_success_total 9610
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 9718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6058
telemt_me_reconnect_success_total 6013
telemt_me_reader_eof_total 6361
telemt_me_idle_close_by_peer_total 6360
telemt_me_route_drop_no_conn_total 301464
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 856498
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4370
telemt_desync_full_logged_total 1574
telemt_desync_suppressed_total 2796
telemt_desync_frames_bucket_total{bucket="1_2"} 875
telemt_desync_frames_bucket_total{bucket="3_10"} 1690
telemt_desync_frames_bucket_total{bucket="gt_10"} 1805
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 6079
telemt_me_writer_restored_same_endpoint_total 6000
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 855930
telemt_user_connections_current{user="hello"} 1786
telemt_user_octets_from_client{user="hello"} 34968146928 (32.57 GB)
telemt_user_octets_to_client{user="hello"} 294994733041 (274.74 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## psb.hosting

Не удалось получить метрики для этого сервера.

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 66707.1 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4600346
telemt_connections_bad_total 286353
telemt_connections_current 5030
telemt_connections_me_current 5030
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 64769
telemt_upstream_connect_attempt_total 68052
telemt_upstream_connect_success_total 63313
telemt_upstream_connect_fail_total 4739
telemt_upstream_connect_attempts_per_request{bucket="1"} 68052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4739
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 10570
telemt_me_reconnect_success_total 7585
telemt_me_reader_eof_total 7926
telemt_me_idle_close_by_peer_total 7925
telemt_me_route_drop_no_conn_total 5332166
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3864780
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12796
telemt_desync_full_logged_total 3724
telemt_desync_suppressed_total 9072
telemt_desync_frames_bucket_total{bucket="1_2"} 2892
telemt_desync_frames_bucket_total{bucket="3_10"} 5054
telemt_desync_frames_bucket_total{bucket="gt_10"} 4850
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 678
telemt_me_writer_removed_unexpected_total 8313
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7581
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 728
telemt_user_connections_total{user="hello"} 3916077
telemt_user_connections_current{user="hello"} 5030
telemt_user_octets_from_client{user="hello"} 46386536108 (43.20 GB)
telemt_user_octets_to_client{user="hello"} 850804785663 (792.37 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1425
telemt_user_unique_ips_recent_window{user="hello"} 887
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 4290.1 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708180
telemt_connections_bad_total 65599
telemt_connections_current 5290
telemt_connections_me_current 5290
telemt_handshake_timeouts_total 12530
telemt_upstream_connect_attempt_total 656
telemt_upstream_connect_success_total 653
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 408
telemt_me_reconnect_success_total 406
telemt_me_reader_eof_total 390
telemt_me_idle_close_by_peer_total 390
telemt_me_route_drop_no_conn_total 918963
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587361
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1594
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1111
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 399
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 587324
telemt_user_connections_current{user="hello"} 5290
telemt_user_octets_from_client{user="hello"} 7829251132 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 107807874724 (100.40 GB)
telemt_user_unique_ips_current{user="hello"} 1609
telemt_user_unique_ips_recent_window{user="hello"} 708
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4225.8 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68882
telemt_connections_bad_total 12938
telemt_connections_current 653
telemt_connections_me_current 653
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 801
telemt_upstream_connect_success_total 794
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 551
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 37038
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66197
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 240
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_restored_same_endpoint_total 540
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 52264
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 561616552 (535.60 MB)
telemt_user_octets_to_client{user="hello"} 20927307472 (19.49 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 66671.7 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2956586
telemt_connections_bad_total 184301
telemt_connections_current 4848
telemt_connections_me_current 4848
telemt_handshake_timeouts_total 54151
telemt_upstream_connect_attempt_total 11742
telemt_upstream_connect_success_total 11668
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 11742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8402
telemt_me_reconnect_success_total 8347
telemt_me_reader_eof_total 8823
telemt_me_idle_close_by_peer_total 8823
telemt_me_route_drop_no_conn_total 1010926
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2486673
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12345
telemt_desync_full_logged_total 4028
telemt_desync_suppressed_total 8317
telemt_desync_frames_bucket_total{bucket="1_2"} 2485
telemt_desync_frames_bucket_total{bucket="3_10"} 4355
telemt_desync_frames_bucket_total{bucket="gt_10"} 5505
telemt_pool_swap_total 68
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8465
telemt_me_writer_restored_same_endpoint_total 8330
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2484764
telemt_user_connections_current{user="hello"} 4848
telemt_user_octets_from_client{user="hello"} 53650147424 (49.97 GB)
telemt_user_octets_to_client{user="hello"} 1299299832292 (1.18 TB)
telemt_user_unique_ips_current{user="hello"} 1531
telemt_user_unique_ips_recent_window{user="hello"} 677
```