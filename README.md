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

# Server Metrics 2026-03-16 07:44:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 120572.9 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554706
telemt_connections_bad_total 5762
telemt_handshake_timeouts_total 19512
telemt_upstream_connect_attempt_total 28226
telemt_upstream_connect_success_total 28094
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 28226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25582
telemt_me_reconnect_success_total 22147
telemt_me_reader_eof_total 23696
telemt_me_idle_close_by_peer_total 23696
telemt_me_route_drop_no_conn_total 524213
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551663
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2698
telemt_desync_full_logged_total 1063
telemt_desync_suppressed_total 1635
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 1039
telemt_desync_frames_bucket_total{bucket="gt_10"} 1078
telemt_pool_swap_total 117
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22500
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22113
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 490484
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 9455653992 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 317623268856 (295.81 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 120579.6 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221337
telemt_connections_bad_total 3155
telemt_handshake_timeouts_total 15081
telemt_upstream_connect_attempt_total 32374
telemt_upstream_connect_success_total 32299
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32849
telemt_me_reconnect_success_total 25930
telemt_me_reader_eof_total 27770
telemt_me_idle_close_by_peer_total 27769
telemt_me_route_drop_no_conn_total 108496
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195275
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26498
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25914
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 194820
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 4509836325 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 109352009392 (101.84 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 120572.4 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239204
telemt_connections_bad_total 5733
telemt_handshake_timeouts_total 4598
telemt_upstream_connect_attempt_total 33507
telemt_upstream_connect_success_total 33499
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34886
telemt_me_reconnect_success_total 27484
telemt_me_reader_eof_total 29586
telemt_me_idle_close_by_peer_total 29585
telemt_me_route_drop_no_conn_total 83638
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191087
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 27981
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27476
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 190798
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 17475292601 (16.28 GB)
telemt_user_octets_to_client{user="hello"} 112044398568 (104.35 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 120571.7 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328171
telemt_connections_bad_total 1336
telemt_handshake_timeouts_total 2936
telemt_upstream_connect_attempt_total 27876
telemt_upstream_connect_success_total 27844
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 27876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22013
telemt_me_reconnect_success_total 21876
telemt_me_reader_eof_total 23363
telemt_me_idle_close_by_peer_total 23362
telemt_me_route_drop_no_conn_total 116042
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302058
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1077
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 458
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22160
telemt_me_writer_restored_same_endpoint_total 21865
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 301938
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 4857255062 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 129549677884 (120.65 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 95643.1 (26h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215993
telemt_connections_bad_total 35913
telemt_handshake_timeouts_total 3612
telemt_upstream_connect_attempt_total 27338
telemt_upstream_connect_success_total 27188
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 27338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116748
telemt_me_reconnect_success_total 22258
telemt_me_reader_eof_total 23640
telemt_me_idle_close_by_peer_total 23640
telemt_me_route_drop_no_conn_total 67714
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170958
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 503
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22440
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22154
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 170588
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2323545193 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 72654059651 (67.66 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 120571.1 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790118
telemt_connections_bad_total 68728
telemt_handshake_timeouts_total 6899
telemt_upstream_connect_attempt_total 25323
telemt_upstream_connect_success_total 25190
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 25323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20554
telemt_me_reconnect_success_total 19207
telemt_me_reader_eof_total 20514
telemt_me_idle_close_by_peer_total 20514
telemt_me_route_drop_no_conn_total 637579
telemt_me_route_drop_channel_closed_total 104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791119
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19476
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19180
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 649754
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 14405986840 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 391869904132 (364.96 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 78
```