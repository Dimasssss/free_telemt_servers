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

# Server Metrics 2026-03-20 05:33:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 44166.3 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849768
telemt_connections_bad_total 55728
telemt_connections_current 1379
telemt_connections_me_current 1379
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20244
telemt_upstream_connect_attempt_total 8647
telemt_upstream_connect_success_total 8548
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 8647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5279
telemt_me_reconnect_success_total 5236
telemt_me_reader_eof_total 5546
telemt_me_idle_close_by_peer_total 5545
telemt_me_route_drop_no_conn_total 236855
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683056
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3627
telemt_desync_full_logged_total 1310
telemt_desync_suppressed_total 2317
telemt_desync_frames_bucket_total{bucket="1_2"} 693
telemt_desync_frames_bucket_total{bucket="3_10"} 1420
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5289
telemt_me_writer_restored_same_endpoint_total 5223
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 684587
telemt_user_connections_current{user="hello"} 1379
telemt_user_octets_from_client{user="hello"} 32989692996 (30.72 GB)
telemt_user_octets_to_client{user="hello"} 235150219645 (219.00 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 519
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 60621.9 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3782597
telemt_connections_bad_total 337403
telemt_connections_current 3821
telemt_connections_me_current 3821
telemt_handshake_timeouts_total 88522
telemt_upstream_connect_attempt_total 11455
telemt_upstream_connect_success_total 11244
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 11455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11250
telemt_me_reconnect_success_total 6999
telemt_me_reader_eof_total 7488
telemt_me_idle_close_by_peer_total 7488
telemt_me_route_drop_no_conn_total 1689467
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3099336
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12677
telemt_desync_full_logged_total 4243
telemt_desync_suppressed_total 8434
telemt_desync_frames_bucket_total{bucket="1_2"} 2418
telemt_desync_frames_bucket_total{bucket="3_10"} 4904
telemt_desync_frames_bucket_total{bucket="gt_10"} 5355
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 7216
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6944
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 3099049
telemt_user_connections_current{user="hello"} 3821
telemt_user_octets_from_client{user="hello"} 46884209658 (43.66 GB)
telemt_user_octets_to_client{user="hello"} 1177589176786 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1391
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 60600.0 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3424962
telemt_connections_bad_total 496709
telemt_connections_current 2959
telemt_connections_me_current 2959
telemt_handshake_timeouts_total 53458
telemt_upstream_connect_attempt_total 9834
telemt_upstream_connect_success_total 9766
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 9834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7691
telemt_me_reconnect_success_total 6748
telemt_me_reader_eof_total 7113
telemt_me_idle_close_by_peer_total 7112
telemt_me_route_drop_no_conn_total 2059935
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2409740
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8840
telemt_desync_full_logged_total 2734
telemt_desync_suppressed_total 6106
telemt_desync_frames_bucket_total{bucket="1_2"} 2194
telemt_desync_frames_bucket_total{bucket="3_10"} 3360
telemt_desync_frames_bucket_total{bucket="gt_10"} 3286
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 6821
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6747
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 2404786
telemt_user_connections_current{user="hello"} 2959
telemt_user_octets_from_client{user="hello"} 36489986564 (33.98 GB)
telemt_user_octets_to_client{user="hello"} 982304935368 (914.84 GB)
telemt_user_unique_ips_current{user="hello"} 1049
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 60587.7 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3151006
telemt_connections_bad_total 234730
telemt_connections_current 3094
telemt_connections_me_current 3094
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 46185
telemt_upstream_connect_attempt_total 67216
telemt_upstream_connect_success_total 62511
telemt_upstream_connect_fail_total 4705
telemt_upstream_connect_attempts_per_request{bucket="1"} 67216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4705
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10052
telemt_me_reconnect_success_total 7085
telemt_me_reader_eof_total 7384
telemt_me_idle_close_by_peer_total 7383
telemt_me_route_drop_no_conn_total 2180721
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2560995
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9642
telemt_desync_full_logged_total 3069
telemt_desync_suppressed_total 6573
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3565
telemt_desync_frames_bucket_total{bucket="gt_10"} 3789
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7796
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7081
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 2611380
telemt_user_connections_current{user="hello"} 3094
telemt_user_octets_from_client{user="hello"} 40080599784 (37.33 GB)
telemt_user_octets_to_client{user="hello"} 775078434467 (721.85 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 114311.1 (31h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6884186
telemt_connections_bad_total 1203596
telemt_connections_current 3676
telemt_connections_me_current 3676
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 121351
telemt_upstream_connect_attempt_total 129745
telemt_upstream_connect_success_total 96443
telemt_upstream_connect_fail_total 33302
telemt_upstream_connect_attempts_per_request{bucket="1"} 129745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33302
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80142
telemt_me_reconnect_success_total 14462
telemt_me_reader_eof_total 15559
telemt_me_idle_close_by_peer_total 15545
telemt_me_route_drop_no_conn_total 2961488
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4861863
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
telemt_desync_total 21077
telemt_desync_full_logged_total 6709
telemt_desync_suppressed_total 14368
telemt_desync_frames_bucket_total{bucket="1_2"} 3747
telemt_desync_frames_bucket_total{bucket="3_10"} 8719
telemt_desync_frames_bucket_total{bucket="gt_10"} 8611
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 14793
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14437
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 4936786
telemt_user_connections_current{user="hello"} 3676
telemt_user_octets_from_client{user="hello"} 78479375300 (73.09 GB)
telemt_user_octets_to_client{user="hello"} 1955809054952 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1199
telemt_user_unique_ips_recent_window{user="hello"} 471
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 60551.0 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1632844
telemt_connections_bad_total 107109
telemt_connections_current 1028
telemt_connections_me_current 1028
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14572
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 60
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473656
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
telemt_desync_total 1565
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 980
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
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
telemt_user_connections_total{user="hello"} 1449268
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 9216995619 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 146634327490 (136.56 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 60552.2 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2475168
telemt_connections_bad_total 155267
telemt_connections_current 2973
telemt_connections_me_current 2973
telemt_handshake_timeouts_total 44860
telemt_upstream_connect_attempt_total 10855
telemt_upstream_connect_success_total 10788
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7813
telemt_me_reconnect_success_total 7763
telemt_me_reader_eof_total 8207
telemt_me_idle_close_by_peer_total 8207
telemt_me_route_drop_no_conn_total 865095
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077643
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10538
telemt_desync_full_logged_total 3429
telemt_desync_suppressed_total 7109
telemt_desync_frames_bucket_total{bucket="1_2"} 2047
telemt_desync_frames_bucket_total{bucket="3_10"} 3715
telemt_desync_frames_bucket_total{bucket="gt_10"} 4776
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 7871
telemt_me_writer_restored_same_endpoint_total 7746
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 2076340
telemt_user_connections_current{user="hello"} 2973
telemt_user_octets_from_client{user="hello"} 44647343708 (41.58 GB)
telemt_user_octets_to_client{user="hello"} 1099438394052 (1023.93 GB)
telemt_user_unique_ips_current{user="hello"} 1007
telemt_user_unique_ips_recent_window{user="hello"} 395
```