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

# Server Metrics 2026-03-19 18:32:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 4507.1 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143406
telemt_connections_bad_total 4645
telemt_connections_current 1490
telemt_connections_me_current 1490
telemt_handshake_timeouts_total 1530
telemt_upstream_connect_attempt_total 645
telemt_upstream_connect_success_total 636
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 397
telemt_me_reconnect_success_total 395
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 45884
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119127
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_restored_same_endpoint_total 382
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 119386
telemt_user_connections_current{user="hello"} 1490
telemt_user_octets_from_client{user="hello"} 1901780356 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 40368096340 (37.60 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 20962.3 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2068021
telemt_connections_bad_total 98822
telemt_connections_current 3806
telemt_connections_me_current 3806
telemt_handshake_timeouts_total 38888
telemt_upstream_connect_attempt_total 4823
telemt_upstream_connect_success_total 4757
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6659
telemt_me_reconnect_success_total 2434
telemt_me_reader_eof_total 2629
telemt_me_idle_close_by_peer_total 2629
telemt_me_route_drop_no_conn_total 1173854
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1725008
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6969
telemt_desync_full_logged_total 2210
telemt_desync_suppressed_total 4759
telemt_desync_frames_bucket_total{bucket="1_2"} 1310
telemt_desync_frames_bucket_total{bucket="3_10"} 2768
telemt_desync_frames_bucket_total{bucket="gt_10"} 2891
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2580
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2379
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1724964
telemt_user_connections_current{user="hello"} 3806
telemt_user_octets_from_client{user="hello"} 25080315042 (23.36 GB)
telemt_user_octets_to_client{user="hello"} 564887457978 (526.09 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1298
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 20940.5 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1890104
telemt_connections_bad_total 222410
telemt_connections_current 2716
telemt_connections_me_current 2716
telemt_handshake_timeouts_total 21167
telemt_upstream_connect_attempt_total 3324
telemt_upstream_connect_success_total 3300
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3124
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 2252
telemt_me_idle_close_by_peer_total 2251
telemt_me_route_drop_no_conn_total 1633400
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1438807
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4682
telemt_desync_full_logged_total 1406
telemt_desync_suppressed_total 3276
telemt_desync_frames_bucket_total{bucket="1_2"} 1205
telemt_desync_frames_bucket_total{bucket="3_10"} 1766
telemt_desync_frames_bucket_total{bucket="gt_10"} 1711
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 2199
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2205
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1435645
telemt_user_connections_current{user="hello"} 2716
telemt_user_octets_from_client{user="hello"} 18728448472 (17.44 GB)
telemt_user_octets_to_client{user="hello"} 459299277488 (427.76 GB)
telemt_user_unique_ips_current{user="hello"} 949
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 20928.0 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1772136
telemt_connections_bad_total 59557
telemt_connections_current 2930
telemt_connections_me_current 2930
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 23706
telemt_upstream_connect_attempt_total 25307
telemt_upstream_connect_success_total 24126
telemt_upstream_connect_fail_total 1181
telemt_upstream_connect_attempts_per_request{bucket="1"} 25307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1181
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4978
telemt_me_reconnect_success_total 2604
telemt_me_reader_eof_total 2695
telemt_me_idle_close_by_peer_total 2694
telemt_me_route_drop_no_conn_total 1553674
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1529560
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5979
telemt_desync_full_logged_total 1867
telemt_desync_suppressed_total 4112
telemt_desync_frames_bucket_total{bucket="1_2"} 1584
telemt_desync_frames_bucket_total{bucket="3_10"} 2200
telemt_desync_frames_bucket_total{bucket="gt_10"} 2195
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3014
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2600
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 1548898
telemt_user_connections_current{user="hello"} 2930
telemt_user_octets_from_client{user="hello"} 26871668077 (25.03 GB)
telemt_user_octets_to_client{user="hello"} 336704790161 (313.58 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 939
telemt_user_unique_ips_recent_window{user="hello"} 421
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 74651.3 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5458630
telemt_connections_bad_total 1006586
telemt_connections_current 3339
telemt_connections_me_current 3339
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 99745
telemt_upstream_connect_attempt_total 64880
telemt_upstream_connect_success_total 62387
telemt_upstream_connect_fail_total 2493
telemt_upstream_connect_attempts_per_request{bucket="1"} 64880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1048
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74891
telemt_me_reconnect_success_total 9482
telemt_me_reader_eof_total 9993
telemt_me_idle_close_by_peer_total 9990
telemt_me_route_drop_no_conn_total 2508108
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3785606
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
telemt_desync_total 16509
telemt_desync_full_logged_total 5063
telemt_desync_suppressed_total 11446
telemt_desync_frames_bucket_total{bucket="1_2"} 2722
telemt_desync_frames_bucket_total{bucket="3_10"} 6884
telemt_desync_frames_bucket_total{bucket="gt_10"} 6903
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 9725
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9458
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 3833735
telemt_user_connections_current{user="hello"} 3339
telemt_user_octets_from_client{user="hello"} 60025757219 (55.90 GB)
telemt_user_octets_to_client{user="hello"} 1408504086272 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1158
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 20892.4 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494609
telemt_connections_bad_total 34517
telemt_connections_current 677
telemt_connections_me_current 677
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10161
telemt_upstream_connect_attempt_total 7123
telemt_upstream_connect_success_total 6926
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 2896
telemt_me_reconnect_success_total 2839
telemt_me_reader_eof_total 2913
telemt_me_idle_close_by_peer_total 2912
telemt_me_route_drop_no_conn_total 354819
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390648
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
telemt_desync_total 1039
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 13
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2857
telemt_me_writer_restored_same_endpoint_total 2830
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 409303
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 4721787120 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 85998837438 (80.09 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 20892.9 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1374464
telemt_connections_bad_total 88027
telemt_connections_current 3018
telemt_connections_me_current 3018
telemt_handshake_timeouts_total 24507
telemt_upstream_connect_attempt_total 3467
telemt_upstream_connect_success_total 3441
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2366
telemt_me_reconnect_success_total 2341
telemt_me_reader_eof_total 2455
telemt_me_idle_close_by_peer_total 2455
telemt_me_route_drop_no_conn_total 530034
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1187718
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6321
telemt_desync_full_logged_total 1933
telemt_desync_suppressed_total 4388
telemt_desync_frames_bucket_total{bucket="1_2"} 1231
telemt_desync_frames_bucket_total{bucket="3_10"} 2203
telemt_desync_frames_bucket_total{bucket="gt_10"} 2887
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 2388
telemt_me_writer_restored_same_endpoint_total 2324
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1187008
telemt_user_connections_current{user="hello"} 3018
telemt_user_octets_from_client{user="hello"} 18498598708 (17.23 GB)
telemt_user_octets_to_client{user="hello"} 523378939436 (487.43 GB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 398
```