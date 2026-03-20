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

# Server Metrics 2026-03-20 02:50:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 34385.2 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638511
telemt_connections_bad_total 40770
telemt_connections_current 827
telemt_connections_me_current 827
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14444
telemt_upstream_connect_attempt_total 7080
telemt_upstream_connect_success_total 6990
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 7080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4177
telemt_me_reconnect_success_total 4138
telemt_me_reader_eof_total 4376
telemt_me_idle_close_by_peer_total 4375
telemt_me_route_drop_no_conn_total 180023
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506302
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2402
telemt_desync_full_logged_total 870
telemt_desync_suppressed_total 1532
telemt_desync_frames_bucket_total{bucket="1_2"} 495
telemt_desync_frames_bucket_total{bucket="3_10"} 862
telemt_desync_frames_bucket_total{bucket="gt_10"} 1045
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4173
telemt_me_writer_restored_same_endpoint_total 4125
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 507735
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 30535971360 (28.44 GB)
telemt_user_octets_to_client{user="hello"} 175733770521 (163.66 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 50839.7 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3118507
telemt_connections_bad_total 152402
telemt_connections_current 1797
telemt_connections_me_current 1797
telemt_handshake_timeouts_total 68658
telemt_upstream_connect_attempt_total 10009
telemt_upstream_connect_success_total 9834
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 10009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10316
telemt_me_reconnect_success_total 6069
telemt_me_reader_eof_total 6495
telemt_me_idle_close_by_peer_total 6495
telemt_me_route_drop_no_conn_total 1528502
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2657812
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11324
telemt_desync_full_logged_total 3741
telemt_desync_suppressed_total 7583
telemt_desync_frames_bucket_total{bucket="1_2"} 2160
telemt_desync_frames_bucket_total{bucket="3_10"} 4429
telemt_desync_frames_bucket_total{bucket="gt_10"} 4735
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6271
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6014
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 2657568
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 40473732346 (37.69 GB)
telemt_user_octets_to_client{user="hello"} 987202728430 (919.40 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 776
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 50817.9 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3028986
telemt_connections_bad_total 479419
telemt_connections_current 1300
telemt_connections_me_current 1300
telemt_handshake_timeouts_total 47414
telemt_upstream_connect_attempt_total 8303
telemt_upstream_connect_success_total 8245
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6644
telemt_me_reconnect_success_total 5709
telemt_me_reader_eof_total 5998
telemt_me_idle_close_by_peer_total 5997
telemt_me_route_drop_no_conn_total 1941233
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2092249
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7868
telemt_desync_full_logged_total 2403
telemt_desync_suppressed_total 5465
telemt_desync_frames_bucket_total{bucket="1_2"} 1925
telemt_desync_frames_bucket_total{bucket="3_10"} 2982
telemt_desync_frames_bucket_total{bucket="gt_10"} 2961
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 5765
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5708
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2087841
telemt_user_connections_current{user="hello"} 1300
telemt_user_octets_from_client{user="hello"} 30594156292 (28.49 GB)
telemt_user_octets_to_client{user="hello"} 805161636336 (749.87 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 50805.7 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2702953
telemt_connections_bad_total 199820
telemt_connections_current 1280
telemt_connections_me_current 1280
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31988
telemt_upstream_connect_attempt_total 56179
telemt_upstream_connect_success_total 51878
telemt_upstream_connect_fail_total 4301
telemt_upstream_connect_attempts_per_request{bucket="1"} 56179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4301
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8948
telemt_me_reconnect_success_total 6093
telemt_me_reader_eof_total 6347
telemt_me_idle_close_by_peer_total 6346
telemt_me_route_drop_no_conn_total 1880922
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2195391
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8483
telemt_desync_full_logged_total 2695
telemt_desync_suppressed_total 5788
telemt_desync_frames_bucket_total{bucket="1_2"} 2087
telemt_desync_frames_bucket_total{bucket="3_10"} 3088
telemt_desync_frames_bucket_total{bucket="gt_10"} 3308
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6729
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6089
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 2237466
telemt_user_connections_current{user="hello"} 1280
telemt_user_octets_from_client{user="hello"} 36228579517 (33.74 GB)
telemt_user_octets_to_client{user="hello"} 635554111441 (591.91 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 104528.8 (29h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6356258
telemt_connections_bad_total 1054401
telemt_connections_current 1420
telemt_connections_me_current 1420
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114901
telemt_upstream_connect_attempt_total 128268
telemt_upstream_connect_success_total 94980
telemt_upstream_connect_fail_total 33288
telemt_upstream_connect_attempts_per_request{bucket="1"} 128268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33288
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79109
telemt_me_reconnect_success_total 13437
telemt_me_reader_eof_total 14466
telemt_me_idle_close_by_peer_total 14452
telemt_me_route_drop_no_conn_total 2818147
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4514541
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
telemt_desync_total 19727
telemt_desync_full_logged_total 6260
telemt_desync_suppressed_total 13467
telemt_desync_frames_bucket_total{bucket="1_2"} 3478
telemt_desync_frames_bucket_total{bucket="3_10"} 8138
telemt_desync_frames_bucket_total{bucket="gt_10"} 8111
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 13748
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13412
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 4589762
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 73181073148 (68.16 GB)
telemt_user_octets_to_client{user="hello"} 1769272085188 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 50768.8 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891334
telemt_connections_bad_total 82111
telemt_connections_current 591
telemt_connections_me_current 591
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13187
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
telemt_me_route_drop_no_conn_total 472421
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
telemt_desync_total 1406
telemt_desync_full_logged_total 531
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 584
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
telemt_user_connections_total{user="hello"} 744523
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 7692742111 (7.16 GB)
telemt_user_octets_to_client{user="hello"} 146574722014 (136.51 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 50770.3 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2092789
telemt_connections_bad_total 123089
telemt_connections_current 1424
telemt_connections_me_current 1424
telemt_handshake_timeouts_total 38459
telemt_upstream_connect_attempt_total 9151
telemt_upstream_connect_success_total 9088
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6587
telemt_me_reconnect_success_total 6542
telemt_me_reader_eof_total 6908
telemt_me_idle_close_by_peer_total 6908
telemt_me_route_drop_no_conn_total 759951
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1787036
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9373
telemt_desync_full_logged_total 3019
telemt_desync_suppressed_total 6354
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 4309
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6637
telemt_me_writer_restored_same_endpoint_total 6525
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1786144
telemt_user_connections_current{user="hello"} 1424
telemt_user_octets_from_client{user="hello"} 30388828132 (28.30 GB)
telemt_user_octets_to_client{user="hello"} 913237548752 (850.52 GB)
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 130
```