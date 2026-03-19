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

# Server Metrics 2026-03-19 22:04:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 17241.7 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402758
telemt_connections_bad_total 20687
telemt_connections_current 895
telemt_connections_me_current 895
telemt_handshake_timeouts_total 5844
telemt_upstream_connect_attempt_total 2843
telemt_upstream_connect_success_total 2816
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1932
telemt_me_reconnect_success_total 1918
telemt_me_reader_eof_total 2026
telemt_me_idle_close_by_peer_total 2026
telemt_me_route_drop_no_conn_total 122026
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320300
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1741
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1137
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 833
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1960
telemt_me_writer_restored_same_endpoint_total 1905
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 320570
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 11221780392 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 119330269120 (111.13 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 33697.3 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2746849
telemt_connections_bad_total 117846
telemt_connections_current 1765
telemt_connections_me_current 1765
telemt_handshake_timeouts_total 54266
telemt_upstream_connect_attempt_total 6894
telemt_upstream_connect_success_total 6785
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 6894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8083
telemt_me_reconnect_success_total 3853
telemt_me_reader_eof_total 4140
telemt_me_idle_close_by_peer_total 4140
telemt_me_route_drop_no_conn_total 1431992
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2344172
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10405
telemt_desync_full_logged_total 3386
telemt_desync_suppressed_total 7019
telemt_desync_frames_bucket_total{bucket="1_2"} 1937
telemt_desync_frames_bucket_total{bucket="3_10"} 4059
telemt_desync_frames_bucket_total{bucket="gt_10"} 4409
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 4022
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3798
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 2344049
telemt_user_connections_current{user="hello"} 1765
telemt_user_octets_from_client{user="hello"} 37124192334 (34.57 GB)
telemt_user_octets_to_client{user="hello"} 835911584138 (778.50 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 33663.4 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2346081
telemt_connections_bad_total 99026
telemt_connections_current 1409
telemt_connections_me_current 1409
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29298
telemt_upstream_connect_attempt_total 35574
telemt_upstream_connect_success_total 33840
telemt_upstream_connect_fail_total 1734
telemt_upstream_connect_attempts_per_request{bucket="1"} 35574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 453
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1734
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6673
telemt_me_reconnect_success_total 4052
telemt_me_reader_eof_total 4193
telemt_me_idle_close_by_peer_total 4192
telemt_me_route_drop_no_conn_total 1818492
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1992927
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8013
telemt_desync_full_logged_total 2500
telemt_desync_suppressed_total 5513
telemt_desync_frames_bucket_total{bucket="1_2"} 1968
telemt_desync_frames_bucket_total{bucket="3_10"} 2909
telemt_desync_frames_bucket_total{bucket="gt_10"} 3136
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 348
telemt_me_writer_removed_unexpected_total 4569
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4048
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 2019861
telemt_user_connections_current{user="hello"} 1409
telemt_user_octets_from_client{user="hello"} 33222077952 (30.94 GB)
telemt_user_octets_to_client{user="hello"} 521167642323 (485.38 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 87386.4 (24h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6014724
telemt_connections_bad_total 1033732
telemt_connections_current 1678
telemt_connections_me_current 1678
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108851
telemt_upstream_connect_attempt_total 66854
telemt_upstream_connect_success_total 64348
telemt_upstream_connect_fail_total 2506
telemt_upstream_connect_attempts_per_request{bucket="1"} 66854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2506
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76215
telemt_me_reconnect_success_total 10797
telemt_me_reader_eof_total 11397
telemt_me_idle_close_by_peer_total 11394
telemt_me_route_drop_no_conn_total 2741008
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4269342
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
telemt_desync_total 18815
telemt_desync_full_logged_total 5843
telemt_desync_suppressed_total 12972
telemt_desync_frames_bucket_total{bucket="1_2"} 3281
telemt_desync_frames_bucket_total{bucket="3_10"} 7741
telemt_desync_frames_bucket_total{bucket="gt_10"} 7793
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 11061
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10773
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 4317393
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 66905649011 (62.31 GB)
telemt_user_octets_to_client{user="hello"} 1668381345776 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 33626.3 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625689
telemt_connections_bad_total 49359
telemt_connections_current 436
telemt_connections_me_current 436
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11944
telemt_upstream_connect_attempt_total 9359
telemt_upstream_connect_success_total 9146
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4527
telemt_me_reconnect_success_total 4448
telemt_me_reader_eof_total 4633
telemt_me_idle_close_by_peer_total 4631
telemt_me_route_drop_no_conn_total 434407
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521874
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
telemt_me_writer_removed_unexpected_total 4487
telemt_me_writer_restored_same_endpoint_total 4439
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 517639
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 6822623804 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 121499302978 (113.16 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 33627.8 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1855398
telemt_connections_bad_total 108591
telemt_connections_current 1535
telemt_connections_me_current 1535
telemt_handshake_timeouts_total 33912
telemt_upstream_connect_attempt_total 5648
telemt_upstream_connect_success_total 5607
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3926
telemt_me_reconnect_success_total 3891
telemt_me_reader_eof_total 4099
telemt_me_idle_close_by_peer_total 4099
telemt_me_route_drop_no_conn_total 693533
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1608279
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8616
telemt_desync_full_logged_total 2710
telemt_desync_suppressed_total 5906
telemt_desync_frames_bucket_total{bucket="1_2"} 1581
telemt_desync_frames_bucket_total{bucket="3_10"} 3003
telemt_desync_frames_bucket_total{bucket="gt_10"} 4032
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 3963
telemt_me_writer_restored_same_endpoint_total 3874
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1607424
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 27459390724 (25.57 GB)
telemt_user_octets_to_client{user="hello"} 802689974604 (747.56 GB)
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 131
```