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

# Server Metrics 2026-03-19 20:43:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 12329.4 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336188
telemt_connections_bad_total 16116
telemt_connections_current 990
telemt_connections_me_current 990
telemt_handshake_timeouts_total 4979
telemt_upstream_connect_attempt_total 1927
telemt_upstream_connect_success_total 1909
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1282
telemt_me_reconnect_success_total 1273
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 102466
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264633
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1330
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 389
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1304
telemt_me_writer_restored_same_endpoint_total 1260
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 264883
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 10611593008 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 96444445272 (89.82 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 28784.8 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2562002
telemt_connections_bad_total 109275
telemt_connections_current 2686
telemt_connections_me_current 2686
telemt_handshake_timeouts_total 49254
telemt_upstream_connect_attempt_total 5942
telemt_upstream_connect_success_total 5853
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 5942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7410
telemt_me_reconnect_success_total 3182
telemt_me_reader_eof_total 3427
telemt_me_idle_close_by_peer_total 3427
telemt_me_route_drop_no_conn_total 1367728
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2178275
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9484
telemt_desync_full_logged_total 3105
telemt_desync_suppressed_total 6379
telemt_desync_frames_bucket_total{bucket="1_2"} 1751
telemt_desync_frames_bucket_total{bucket="3_10"} 3714
telemt_desync_frames_bucket_total{bucket="gt_10"} 4019
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3345
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3127
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 2178227
telemt_user_connections_current{user="hello"} 2686
telemt_user_octets_from_client{user="hello"} 33591756898 (31.28 GB)
telemt_user_octets_to_client{user="hello"} 768948116246 (716.14 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 28763.4 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2438156
telemt_connections_bad_total 376881
telemt_connections_current 1977
telemt_connections_me_current 1977
telemt_handshake_timeouts_total 28283
telemt_upstream_connect_attempt_total 4432
telemt_upstream_connect_success_total 4402
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3879
telemt_me_reconnect_success_total 2957
telemt_me_reader_eof_total 3058
telemt_me_idle_close_by_peer_total 3057
telemt_me_route_drop_no_conn_total 1806515
telemt_me_route_drop_channel_closed_total 163
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1762060
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6617
telemt_desync_full_logged_total 1974
telemt_desync_suppressed_total 4643
telemt_desync_frames_bucket_total{bucket="1_2"} 1700
telemt_desync_frames_bucket_total{bucket="3_10"} 2485
telemt_desync_frames_bucket_total{bucket="gt_10"} 2432
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 2968
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2956
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 1758416
telemt_user_connections_current{user="hello"} 1978
telemt_user_octets_from_client{user="hello"} 25084528904 (23.36 GB)
telemt_user_octets_to_client{user="hello"} 616791269864 (574.43 GB)
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 28765.7 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2195736
telemt_connections_bad_total 86161
telemt_connections_current 2006
telemt_connections_me_current 2006
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27462
telemt_upstream_connect_attempt_total 31711
telemt_upstream_connect_success_total 30160
telemt_upstream_connect_fail_total 1551
telemt_upstream_connect_attempts_per_request{bucket="1"} 31711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1551
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5959
telemt_me_reconnect_success_total 3417
telemt_me_reader_eof_total 3545
telemt_me_idle_close_by_peer_total 3544
telemt_me_route_drop_no_conn_total 1773881
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1876019
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7517
telemt_desync_full_logged_total 2337
telemt_desync_suppressed_total 5180
telemt_desync_frames_bucket_total{bucket="1_2"} 1873
telemt_desync_frames_bucket_total{bucket="3_10"} 2721
telemt_desync_frames_bucket_total{bucket="gt_10"} 2923
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 291
telemt_me_writer_removed_unexpected_total 3881
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3413
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1900209
telemt_user_connections_current{user="hello"} 2006
telemt_user_octets_from_client{user="hello"} 31412578636 (29.26 GB)
telemt_user_octets_to_client{user="hello"} 459073401034 (427.55 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 82473.9 (22h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5866606
telemt_connections_bad_total 1029048
telemt_connections_current 2496
telemt_connections_me_current 2496
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107146
telemt_upstream_connect_attempt_total 66058
telemt_upstream_connect_success_total 63556
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75673
telemt_me_reconnect_success_total 10256
telemt_me_reader_eof_total 10826
telemt_me_idle_close_by_peer_total 10823
telemt_me_route_drop_no_conn_total 2686508
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4136157
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
telemt_desync_total 18152
telemt_desync_full_logged_total 5632
telemt_desync_suppressed_total 12520
telemt_desync_frames_bucket_total{bucket="1_2"} 3104
telemt_desync_frames_bucket_total{bucket="3_10"} 7518
telemt_desync_frames_bucket_total{bucket="gt_10"} 7530
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 10515
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10232
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 4184218
telemt_user_connections_current{user="hello"} 2496
telemt_user_octets_from_client{user="hello"} 65298155011 (60.81 GB)
telemt_user_octets_to_client{user="hello"} 1593664571440 (1.45 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 880
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 28713.9 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590800
telemt_connections_bad_total 45862
telemt_connections_current 563
telemt_connections_me_current 563
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11434
telemt_upstream_connect_attempt_total 8357
telemt_upstream_connect_success_total 8160
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3785
telemt_me_reconnect_success_total 3723
telemt_me_reader_eof_total 3861
telemt_me_idle_close_by_peer_total 3860
telemt_me_route_drop_no_conn_total 391078
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470293
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
telemt_desync_total 1226
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 821
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 138
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3756
telemt_me_writer_restored_same_endpoint_total 3714
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 488932
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 5492901240 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 106060013014 (98.78 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 28715.3 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1728489
telemt_connections_bad_total 102689
telemt_connections_current 2115
telemt_connections_me_current 2115
telemt_handshake_timeouts_total 28361
telemt_upstream_connect_attempt_total 4744
telemt_upstream_connect_success_total 4709
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3286
telemt_me_reconnect_success_total 3254
telemt_me_reader_eof_total 3417
telemt_me_idle_close_by_peer_total 3417
telemt_me_route_drop_no_conn_total 652413
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1502767
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7943
telemt_desync_full_logged_total 2458
telemt_desync_suppressed_total 5485
telemt_desync_frames_bucket_total{bucket="1_2"} 1488
telemt_desync_frames_bucket_total{bucket="3_10"} 2760
telemt_desync_frames_bucket_total{bucket="gt_10"} 3695
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3314
telemt_me_writer_restored_same_endpoint_total 3237
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1501952
telemt_user_connections_current{user="hello"} 2115
telemt_user_octets_from_client{user="hello"} 25556926180 (23.80 GB)
telemt_user_octets_to_client{user="hello"} 727686680500 (677.71 GB)
telemt_user_unique_ips_current{user="hello"} 740
telemt_user_unique_ips_recent_window{user="hello"} 219
```