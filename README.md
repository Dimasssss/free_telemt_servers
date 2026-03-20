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

# Server Metrics 2026-03-20 02:20:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 32549.4 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607409
telemt_connections_bad_total 38644
telemt_connections_current 818
telemt_connections_me_current 818
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10129
telemt_upstream_connect_attempt_total 6779
telemt_upstream_connect_success_total 6692
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3965
telemt_me_reconnect_success_total 3928
telemt_me_reader_eof_total 4148
telemt_me_idle_close_by_peer_total 4147
telemt_me_route_drop_no_conn_total 173474
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484987
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2263
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 1445
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 1015
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3959
telemt_me_writer_restored_same_endpoint_total 3915
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 486422
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 30217790000 (28.14 GB)
telemt_user_octets_to_client{user="hello"} 170157466809 (158.47 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 49004.1 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3059342
telemt_connections_bad_total 137071
telemt_connections_current 1573
telemt_connections_me_current 1573
telemt_handshake_timeouts_total 67456
telemt_upstream_connect_attempt_total 9690
telemt_upstream_connect_success_total 9526
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 9690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10094
telemt_me_reconnect_success_total 5849
telemt_me_reader_eof_total 6259
telemt_me_idle_close_by_peer_total 6259
telemt_me_route_drop_no_conn_total 1515819
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2616707
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11266
telemt_desync_full_logged_total 3717
telemt_desync_suppressed_total 7549
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 4403
telemt_desync_frames_bucket_total{bucket="gt_10"} 4711
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 6048
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5794
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 2616480
telemt_user_connections_current{user="hello"} 1573
telemt_user_octets_from_client{user="hello"} 39914715766 (37.17 GB)
telemt_user_octets_to_client{user="hello"} 968781163226 (902.25 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 697
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 48982.7 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2994277
telemt_connections_bad_total 477070
telemt_connections_current 1229
telemt_connections_me_current 1229
telemt_handshake_timeouts_total 45230
telemt_upstream_connect_attempt_total 7983
telemt_upstream_connect_success_total 7925
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6410
telemt_me_reconnect_success_total 5476
telemt_me_reader_eof_total 5752
telemt_me_idle_close_by_peer_total 5751
telemt_me_route_drop_no_conn_total 1931488
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2066193
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7761
telemt_desync_full_logged_total 2363
telemt_desync_suppressed_total 5398
telemt_desync_frames_bucket_total{bucket="1_2"} 1908
telemt_desync_frames_bucket_total{bucket="3_10"} 2948
telemt_desync_frames_bucket_total{bucket="gt_10"} 2905
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5529
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5475
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2061813
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 30347808308 (28.26 GB)
telemt_user_octets_to_client{user="hello"} 793674895568 (739.17 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 48970.3 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2637170
telemt_connections_bad_total 164437
telemt_connections_current 1167
telemt_connections_me_current 1167
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31604
telemt_upstream_connect_attempt_total 55852
telemt_upstream_connect_success_total 51561
telemt_upstream_connect_fail_total 4291
telemt_upstream_connect_attempts_per_request{bucket="1"} 55852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 530
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4291
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8710
telemt_me_reconnect_success_total 5864
telemt_me_reader_eof_total 6103
telemt_me_idle_close_by_peer_total 6102
telemt_me_route_drop_no_conn_total 1873473
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2168978
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8381
telemt_desync_full_logged_total 2654
telemt_desync_suppressed_total 5727
telemt_desync_frames_bucket_total{bucket="1_2"} 2065
telemt_desync_frames_bucket_total{bucket="3_10"} 3050
telemt_desync_frames_bucket_total{bucket="gt_10"} 3266
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6496
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5860
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 2211050
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 35908783289 (33.44 GB)
telemt_user_octets_to_client{user="hello"} 623967542857 (581.12 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 102693.5 (28h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6317186
telemt_connections_bad_total 1048130
telemt_connections_current 1348
telemt_connections_me_current 1348
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114308
telemt_upstream_connect_attempt_total 127937
telemt_upstream_connect_success_total 94650
telemt_upstream_connect_fail_total 33287
telemt_upstream_connect_attempts_per_request{bucket="1"} 127937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33287
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78871
telemt_me_reconnect_success_total 13200
telemt_me_reader_eof_total 14210
telemt_me_idle_close_by_peer_total 14196
telemt_me_route_drop_no_conn_total 2809196
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4483633
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
telemt_desync_total 19630
telemt_desync_full_logged_total 6223
telemt_desync_suppressed_total 13407
telemt_desync_frames_bucket_total{bucket="1_2"} 3457
telemt_desync_frames_bucket_total{bucket="3_10"} 8090
telemt_desync_frames_bucket_total{bucket="gt_10"} 8083
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 13509
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13175
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4558844
telemt_user_connections_current{user="hello"} 1348
telemt_user_octets_from_client{user="hello"} 72831172784 (67.83 GB)
telemt_user_octets_to_client{user="hello"} 1751807004164 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 48933.3 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776580
telemt_connections_bad_total 79236
telemt_connections_current 572
telemt_connections_me_current 572
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13113
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 471993
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 633548
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 7466831347 (6.95 GB)
telemt_user_octets_to_client{user="hello"} 146547581058 (136.48 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 48934.8 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2061716
telemt_connections_bad_total 121041
telemt_connections_current 1341
telemt_connections_me_current 1341
telemt_handshake_timeouts_total 38111
telemt_upstream_connect_attempt_total 8805
telemt_upstream_connect_success_total 8744
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6329
telemt_me_reconnect_success_total 6284
telemt_me_reader_eof_total 6637
telemt_me_idle_close_by_peer_total 6637
telemt_me_route_drop_no_conn_total 751520
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1765003
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9317
telemt_desync_full_logged_total 2998
telemt_desync_suppressed_total 6319
telemt_desync_frames_bucket_total{bucket="1_2"} 1768
telemt_desync_frames_bucket_total{bucket="3_10"} 3265
telemt_desync_frames_bucket_total{bucket="gt_10"} 4284
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6377
telemt_me_writer_restored_same_endpoint_total 6267
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 1764111
telemt_user_connections_current{user="hello"} 1341
telemt_user_octets_from_client{user="hello"} 30125337252 (28.06 GB)
telemt_user_octets_to_client{user="hello"} 897816665716 (836.16 GB)
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 110
```