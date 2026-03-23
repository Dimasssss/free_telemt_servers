# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 04:54:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 114508.1 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3902034
telemt_connections_bad_total 384432
telemt_connections_current 1307
telemt_connections_me_current 1307
telemt_handshake_timeouts_total 131361
telemt_upstream_connect_attempt_total 42685
telemt_upstream_connect_success_total 42684
telemt_upstream_connect_attempts_per_request{bucket="1"} 42684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1470
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 3049219
telemt_me_route_drop_channel_closed_total 1257
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3176227
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 896
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 13617
telemt_desync_full_logged_total 4353
telemt_desync_suppressed_total 9264
telemt_desync_frames_bucket_total{bucket="1_2"} 3570
telemt_desync_frames_bucket_total{bucket="3_10"} 5011
telemt_desync_frames_bucket_total{bucket="gt_10"} 5036
telemt_pool_swap_total 127
telemt_pool_force_close_total 3881
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 39117
telemt_me_writer_removed_unexpected_total 663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2798
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3816
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35236
telemt_me_writer_teardown_success_total{mode="normal"} 39395
telemt_me_writer_teardown_noop_total 39130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 389.595425
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 3164668
telemt_user_connections_current{user="hello"} 1307
telemt_user_octets_from_client{user="hello"} 44354090364 (41.31 GB)
telemt_user_octets_to_client{user="hello"} 868623004564 (808.97 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 127874.0 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4115056
telemt_connections_bad_total 383172
telemt_connections_current 738
telemt_connections_me_current 738
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 105270
telemt_upstream_connect_attempt_total 80050
telemt_upstream_connect_success_total 79095
telemt_upstream_connect_fail_total 846
telemt_upstream_connect_attempts_per_request{bucket="1"} 79941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 846
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10767
telemt_me_reconnect_success_total 3867
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3843
telemt_me_route_drop_no_conn_total 3662234
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3265682
telemt_me_endpoint_quarantine_total 1037
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 24
telemt_desync_total 13425
telemt_desync_full_logged_total 7562
telemt_desync_suppressed_total 5863
telemt_desync_frames_bucket_total{bucket="1_2"} 3059
telemt_desync_frames_bucket_total{bucket="3_10"} 5268
telemt_desync_frames_bucket_total{bucket="gt_10"} 5098
telemt_pool_swap_total 120
telemt_pool_force_close_total 3345
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 259
telemt_me_draining_writers_reap_progress_total 53601
telemt_me_writer_removed_unexpected_total 3765
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2863
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50256
telemt_me_writer_teardown_success_total{mode="normal"} 57406
telemt_me_writer_teardown_noop_total 53602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111008
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.822342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111008
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 259
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 3426
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 3280133
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 44195585711 (41.16 GB)
telemt_user_octets_to_client{user="hello"} 823206091249 (766.67 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 202734.2 (56h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16593845
telemt_connections_bad_total 1682106
telemt_connections_current 1188
telemt_connections_me_current 1188
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 404719
telemt_upstream_connect_attempt_total 91239
telemt_upstream_connect_success_total 91132
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3201
telemt_me_reconnect_success_total 1674
telemt_me_reader_eof_total 1631
telemt_me_idle_close_by_peer_total 1629
telemt_me_route_drop_no_conn_total 14096633
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13178974
telemt_me_endpoint_quarantine_total 1378
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1536
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 54897
telemt_desync_full_logged_total 17532
telemt_desync_suppressed_total 37365
telemt_desync_frames_bucket_total{bucket="1_2"} 12238
telemt_desync_frames_bucket_total{bucket="3_10"} 21495
telemt_desync_frames_bucket_total{bucket="gt_10"} 21164
telemt_pool_swap_total 220
telemt_pool_force_close_total 7070
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1096
telemt_me_draining_writers_reap_progress_total 70138
telemt_me_writer_removed_unexpected_total 1565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5895
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65093
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63068
telemt_me_writer_teardown_success_total{mode="normal"} 70988
telemt_me_writer_teardown_noop_total 70192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141180
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.837531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141180
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1096
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1452
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 13178847
telemt_user_connections_current{user="hello"} 1188
telemt_user_octets_from_client{user="hello"} 199620007025 (185.91 GB)
telemt_user_octets_to_client{user="hello"} 3571939560267 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 202735.4 (56h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12118611
telemt_connections_bad_total 1283171
telemt_connections_current 941
telemt_connections_me_current 941
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 350683
telemt_upstream_connect_attempt_total 105586
telemt_upstream_connect_success_total 104174
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4648
telemt_me_reconnect_success_total 1998
telemt_me_reader_eof_total 1857
telemt_me_idle_close_by_peer_total 1857
telemt_me_route_drop_no_conn_total 4599515
telemt_me_route_drop_channel_closed_total 503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8966902
telemt_me_endpoint_quarantine_total 1388
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1552
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39394
telemt_desync_full_logged_total 13265
telemt_desync_suppressed_total 26129
telemt_desync_frames_bucket_total{bucket="1_2"} 9763
telemt_desync_frames_bucket_total{bucket="3_10"} 15146
telemt_desync_frames_bucket_total{bucket="gt_10"} 14485
telemt_pool_swap_total 217
telemt_pool_force_close_total 6416
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 718
telemt_me_draining_writers_reap_progress_total 68206
telemt_me_writer_removed_unexpected_total 1889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5983
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61790
telemt_me_writer_teardown_success_total{mode="normal"} 69956
telemt_me_writer_teardown_noop_total 68231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138187
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.609376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138187
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 718
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1704
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8904494
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 219387190676 (204.32 GB)
telemt_user_octets_to_client{user="hello"} 4013963500735 (3.65 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 202699.3 (56h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11268356
telemt_connections_bad_total 1031246
telemt_connections_current 721
telemt_connections_me_current 721
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 351794
telemt_upstream_connect_attempt_total 89968
telemt_upstream_connect_success_total 88394
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5878
telemt_me_reconnect_success_total 2466
telemt_me_reader_eof_total 2212
telemt_me_idle_close_by_peer_total 2211
telemt_me_route_drop_no_conn_total 5367882
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8477735
telemt_me_endpoint_quarantine_total 1437
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1514
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 38583
telemt_desync_full_logged_total 12803
telemt_desync_suppressed_total 25780
telemt_desync_frames_bucket_total{bucket="1_2"} 9746
telemt_desync_frames_bucket_total{bucket="3_10"} 14772
telemt_desync_frames_bucket_total{bucket="gt_10"} 14065
telemt_pool_swap_total 213
telemt_pool_force_close_total 6302
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 761
telemt_me_draining_writers_reap_progress_total 68776
telemt_me_writer_removed_unexpected_total 2358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64348
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62474
telemt_me_writer_teardown_success_total{mode="normal"} 71070
telemt_me_writer_teardown_noop_total 68847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.953962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 761
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8469602
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 193821247695 (180.51 GB)
telemt_user_octets_to_client{user="hello"} 3515303759109 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72979.9 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11564195
telemt_connections_bad_total 680200
telemt_connections_current 1599
telemt_connections_me_current 1599
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 308072
telemt_upstream_connect_attempt_total 65256
telemt_upstream_connect_success_total 61817
telemt_upstream_connect_fail_total 2216
telemt_upstream_connect_attempts_per_request{bucket="1"} 64033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2216
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8289
telemt_me_reconnect_success_total 1480
telemt_me_reader_eof_total 949
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 25351714
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9580100
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 103
telemt_me_single_endpoint_outage_exit_total 103
telemt_me_single_endpoint_outage_reconnect_attempt_total 201
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 201
telemt_me_single_endpoint_shadow_rotate_total 586
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 31
telemt_desync_total 17122
telemt_desync_full_logged_total 4746
telemt_desync_suppressed_total 12376
telemt_desync_frames_bucket_total{bucket="1_2"} 3306
telemt_desync_frames_bucket_total{bucket="3_10"} 7000
telemt_desync_frames_bucket_total{bucket="gt_10"} 6816
telemt_pool_swap_total 75
telemt_pool_force_close_total 2341
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 518
telemt_me_draining_writers_reap_progress_total 24153
telemt_me_writer_removed_unexpected_total 1343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3081
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22366
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21812
telemt_me_writer_teardown_success_total{mode="normal"} 25447
telemt_me_writer_teardown_noop_total 24172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49619
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.650164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49619
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 518
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9606516
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 90163039426 (83.97 GB)
telemt_user_octets_to_client{user="hello"} 697502153505 (649.60 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 202706.2 (56h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11226159
telemt_connections_bad_total 990181
telemt_connections_current 913
telemt_connections_me_current 913
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 248792
telemt_upstream_connect_attempt_total 118903
telemt_upstream_connect_success_total 117667
telemt_upstream_connect_fail_total 1059
telemt_upstream_connect_attempts_per_request{bucket="1"} 118726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1059
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73513
telemt_me_reconnect_success_total 3245
telemt_me_reader_eof_total 2941
telemt_me_idle_close_by_peer_total 2938
telemt_me_route_drop_no_conn_total 5305542
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8837843
telemt_me_endpoint_quarantine_total 1380
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1542
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 47096
telemt_desync_full_logged_total 16190
telemt_desync_suppressed_total 30906
telemt_desync_frames_bucket_total{bucket="1_2"} 9557
telemt_desync_frames_bucket_total{bucket="3_10"} 18066
telemt_desync_frames_bucket_total{bucket="gt_10"} 19473
telemt_pool_swap_total 209
telemt_pool_force_close_total 6029
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 72854
telemt_me_writer_removed_unexpected_total 2958
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5280
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66825
telemt_me_writer_teardown_success_total{mode="normal"} 75859
telemt_me_writer_teardown_noop_total 72855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148714
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.356255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148714
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2732
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8840570
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 198559052417 (184.92 GB)
telemt_user_octets_to_client{user="hello"} 3380616458636 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 139542.4 (38h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11985889
telemt_connections_bad_total 492612
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4836475
telemt_upstream_connect_attempt_total 67797
telemt_upstream_connect_success_total 67316
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 67783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_reconnect_attempts_total 49265
telemt_me_reconnect_success_total 1946
telemt_me_reader_eof_total 1628
telemt_me_idle_close_by_peer_total 1627
telemt_me_route_drop_no_conn_total 4129758
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5761165
telemt_me_endpoint_quarantine_total 960
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1076
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 10
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32413
telemt_desync_full_logged_total 11071
telemt_desync_suppressed_total 21342
telemt_desync_frames_bucket_total{bucket="1_2"} 6500
telemt_desync_frames_bucket_total{bucket="3_10"} 12772
telemt_desync_frames_bucket_total{bucket="gt_10"} 13141
telemt_pool_swap_total 148
telemt_pool_force_close_total 4202
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 52700
telemt_me_writer_removed_unexpected_total 1668
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48498
telemt_me_writer_teardown_success_total{mode="normal"} 54422
telemt_me_writer_teardown_noop_total 52707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.807758
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 2749
telemt_me_writer_restored_same_endpoint_total 1721
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5753140
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 121401761448 (113.06 GB)
telemt_user_octets_to_client{user="hello"} 2240905848158 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 120512.9 (33h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1656492
telemt_connections_bad_total 37224
telemt_connections_current 828
telemt_connections_me_current 828
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34608
telemt_upstream_connect_attempt_total 56873
telemt_upstream_connect_success_total 56697
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 830
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2456
telemt_me_reconnect_success_total 999
telemt_me_reader_eof_total 994
telemt_me_idle_close_by_peer_total 994
telemt_me_route_drop_no_conn_total 552285
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1472466
telemt_me_endpoint_quarantine_total 1019
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 995
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 10223
telemt_desync_full_logged_total 2883
telemt_desync_suppressed_total 7340
telemt_desync_frames_bucket_total{bucket="1_2"} 3221
telemt_desync_frames_bucket_total{bucket="3_10"} 3851
telemt_desync_frames_bucket_total{bucket="gt_10"} 3151
telemt_pool_swap_total 130
telemt_pool_force_close_total 3276
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 48486
telemt_me_writer_removed_unexpected_total 957
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3657
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45830
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45210
telemt_me_writer_teardown_success_total{mode="normal"} 49487
telemt_me_writer_teardown_noop_total 48490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97977
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.574472
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97977
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1468093
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 27268930733 (25.40 GB)
telemt_user_octets_to_client{user="hello"} 607979308195 (566.22 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 202710.7 (56h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13514208
telemt_connections_bad_total 1631354
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_handshake_timeouts_total 395932
telemt_upstream_connect_attempt_total 81712
telemt_upstream_connect_success_total 81349
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 81575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3214
telemt_me_reconnect_success_total 1611
telemt_me_reader_eof_total 1602
telemt_me_idle_close_by_peer_total 1602
telemt_me_route_drop_no_conn_total 4517411
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10189006
telemt_me_endpoint_quarantine_total 1502
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1541
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 42740
telemt_desync_full_logged_total 13950
telemt_desync_suppressed_total 28790
telemt_desync_frames_bucket_total{bucket="1_2"} 10406
telemt_desync_frames_bucket_total{bucket="3_10"} 15688
telemt_desync_frames_bucket_total{bucket="gt_10"} 16646
telemt_pool_swap_total 225
telemt_pool_force_close_total 5874
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 73966
telemt_me_writer_removed_unexpected_total 1532
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69856
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68092
telemt_me_writer_teardown_success_total{mode="normal"} 75558
telemt_me_writer_teardown_noop_total 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149526
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.978220
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149526
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 1418
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 10155463
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 196466099780 (182.97 GB)
telemt_user_octets_to_client{user="hello"} 4525761415108 (4.12 TB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 388
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 202707.2 (56h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11832951
telemt_connections_bad_total 1386057
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 318572
telemt_upstream_connect_attempt_total 109564
telemt_upstream_connect_success_total 108619
telemt_upstream_connect_fail_total 736
telemt_upstream_connect_attempts_per_request{bucket="1"} 109355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 736
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11064
telemt_me_reconnect_success_total 2749
telemt_me_reader_eof_total 2552
telemt_me_idle_close_by_peer_total 2551
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5684387
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9107079
telemt_me_endpoint_quarantine_total 1675
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1547
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 42408
telemt_desync_full_logged_total 13651
telemt_desync_suppressed_total 28757
telemt_desync_frames_bucket_total{bucket="1_2"} 11024
telemt_desync_frames_bucket_total{bucket="3_10"} 15564
telemt_desync_frames_bucket_total{bucket="gt_10"} 15820
telemt_pool_swap_total 215
telemt_pool_force_close_total 5637
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 74310
telemt_me_writer_removed_unexpected_total 2588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68673
telemt_me_writer_teardown_success_total{mode="normal"} 76998
telemt_me_writer_teardown_noop_total 74315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151313
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.671131
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151313
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 2191
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 9111543
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 158932421564 (148.02 GB)
telemt_user_octets_to_client{user="hello"} 3566744101642 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 367
```