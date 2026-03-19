# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-19 06:23:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 30919.5 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485980
telemt_connections_bad_total 50497
telemt_connections_current 1243
telemt_connections_me_current 1243
telemt_handshake_timeouts_total 22133
telemt_upstream_connect_attempt_total 6011
telemt_upstream_connect_success_total 5907
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 6011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5493
telemt_me_reconnect_success_total 4350
telemt_me_reader_eof_total 4618
telemt_me_idle_close_by_peer_total 4617
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 129915
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362329
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2289
telemt_desync_full_logged_total 660
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 788
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4429
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4333
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 359580
telemt_user_connections_current{user="hello"} 1243
telemt_user_octets_from_client{user="hello"} 4727111008 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 122505162736 (114.09 GB)
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 30923.5 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024723
telemt_connections_bad_total 59580
telemt_connections_current 3473
telemt_connections_me_current 3473
telemt_handshake_timeouts_total 28273
telemt_upstream_connect_attempt_total 5837
telemt_upstream_connect_success_total 5730
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 5837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 5304
telemt_me_reconnect_success_total 4158
telemt_me_reader_eof_total 4417
telemt_me_idle_close_by_peer_total 4417
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 329564
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846076
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3563
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2344
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 1342
telemt_desync_frames_bucket_total{bucket="gt_10"} 1580
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4270
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4138
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 846032
telemt_user_connections_current{user="hello"} 3473
telemt_user_octets_from_client{user="hello"} 18589497320 (17.31 GB)
telemt_user_octets_to_client{user="hello"} 376467321532 (350.61 GB)
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 30920.8 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880653
telemt_connections_bad_total 142794
telemt_connections_current 2944
telemt_connections_me_current 2944
telemt_handshake_timeouts_total 27378
telemt_upstream_connect_attempt_total 5700
telemt_upstream_connect_success_total 5700
telemt_upstream_connect_attempts_per_request{bucket="1"} 5700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4151
telemt_me_reconnect_success_total 4132
telemt_me_reader_eof_total 4377
telemt_me_idle_close_by_peer_total 4377
telemt_me_route_drop_no_conn_total 276109
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643951
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3286
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 2238
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 1175
telemt_desync_frames_bucket_total{bucket="gt_10"} 1515
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4208
telemt_me_writer_restored_same_endpoint_total 4116
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 643696
telemt_user_connections_current{user="hello"} 2944
telemt_user_octets_from_client{user="hello"} 12269574956 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 368645886708 (343.33 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 30973.9 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 945095
telemt_connections_bad_total 88282
telemt_connections_current 2683
telemt_connections_me_current 2683
telemt_handshake_timeouts_total 22859
telemt_upstream_connect_attempt_total 5490
telemt_upstream_connect_success_total 5490
telemt_upstream_connect_attempts_per_request{bucket="1"} 5490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4967
telemt_me_reconnect_success_total 3916
telemt_me_reader_eof_total 4164
telemt_me_idle_close_by_peer_total 4163
telemt_me_route_drop_no_conn_total 294085
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2465
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 1584
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 1044
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4006
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3892
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 632117
telemt_user_connections_current{user="hello"} 2683
telemt_user_octets_from_client{user="hello"} 9879430324 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 241981285500 (225.36 GB)
telemt_user_unique_ips_current{user="hello"} 915
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 30917.4 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1146660
telemt_connections_bad_total 321644
telemt_connections_current 3037
telemt_connections_me_current 3037
telemt_handshake_timeouts_total 28812
telemt_upstream_connect_attempt_total 5535
telemt_upstream_connect_success_total 5500
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 3961
telemt_me_reconnect_success_total 3934
telemt_me_reader_eof_total 4165
telemt_me_idle_close_by_peer_total 4165
telemt_me_route_drop_no_conn_total 280948
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678652
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3354
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1476
telemt_desync_frames_bucket_total{bucket="gt_10"} 1119
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 3978
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 678536
telemt_user_connections_current{user="hello"} 3037
telemt_user_octets_from_client{user="hello"} 16784192900 (15.63 GB)
telemt_user_octets_to_client{user="hello"} 362023193036 (337.16 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 30928.9 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192315
telemt_connections_bad_total 12195
telemt_connections_current 679
telemt_connections_me_current 679
telemt_handshake_timeouts_total 1533
telemt_upstream_connect_attempt_total 8354
telemt_upstream_connect_success_total 8143
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 8354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 11020
telemt_me_reconnect_success_total 6582
telemt_me_reader_eof_total 6972
telemt_me_idle_close_by_peer_total 6972
telemt_me_route_drop_no_conn_total 77735
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167757
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 246
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6746
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6552
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 167749
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 2754715180 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 91107928992 (84.85 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 30919.7 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702594
telemt_connections_bad_total 84399
telemt_connections_current 2659
telemt_connections_me_current 2659
telemt_handshake_timeouts_total 30491
telemt_upstream_connect_attempt_total 6219
telemt_upstream_connect_success_total 6219
telemt_upstream_connect_attempts_per_request{bucket="1"} 6219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4676
telemt_me_reconnect_success_total 4662
telemt_me_reader_eof_total 4932
telemt_me_idle_close_by_peer_total 4932
telemt_me_route_drop_no_conn_total 247027
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563119
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3205
telemt_desync_full_logged_total 1140
telemt_desync_suppressed_total 2065
telemt_desync_frames_bucket_total{bucket="1_2"} 629
telemt_desync_frames_bucket_total{bucket="3_10"} 1231
telemt_desync_frames_bucket_total{bucket="gt_10"} 1345
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4715
telemt_me_writer_restored_same_endpoint_total 4647
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 562923
telemt_user_connections_current{user="hello"} 2659
telemt_user_octets_from_client{user="hello"} 7629528704 (7.11 GB)
telemt_user_octets_to_client{user="hello"} 319160708244 (297.24 GB)
telemt_user_unique_ips_current{user="hello"} 898
telemt_user_unique_ips_recent_window{user="hello"} 320
```