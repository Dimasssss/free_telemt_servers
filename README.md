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

# Server Metrics 2026-03-23 04:49:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 114202.7 (31h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3890951
telemt_connections_bad_total 383226
telemt_connections_current 1423
telemt_connections_me_current 1423
telemt_handshake_timeouts_total 130802
telemt_upstream_connect_attempt_total 42531
telemt_upstream_connect_success_total 42530
telemt_upstream_connect_attempts_per_request{bucket="1"} 42530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 666
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 3046069
telemt_me_route_drop_channel_closed_total 1255
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3167388
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 811
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 892
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
telemt_me_writers_active_current 45
telemt_desync_total 13568
telemt_desync_full_logged_total 4343
telemt_desync_suppressed_total 9225
telemt_desync_frames_bucket_total{bucket="1_2"} 3565
telemt_desync_frames_bucket_total{bucket="3_10"} 4992
telemt_desync_frames_bucket_total{bucket="gt_10"} 5011
telemt_pool_swap_total 126
telemt_pool_force_close_total 3849
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 697
telemt_me_draining_writers_reap_progress_total 38969
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2784
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36462
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3785
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35120
telemt_me_writer_teardown_success_total{mode="normal"} 39246
telemt_me_writer_teardown_noop_total 38982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 389.127567
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 697
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 3155850
telemt_user_connections_current{user="hello"} 1423
telemt_user_octets_from_client{user="hello"} 44265269672 (41.23 GB)
telemt_user_octets_to_client{user="hello"} 865164956544 (805.75 GB)
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 127569.6 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4110146
telemt_connections_bad_total 382995
telemt_connections_current 557
telemt_connections_me_current 557
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 104790
telemt_upstream_connect_attempt_total 79910
telemt_upstream_connect_success_total 78957
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 79802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10767
telemt_me_reconnect_success_total 3867
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3843
telemt_me_route_drop_no_conn_total 3661259
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3262368
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
telemt_desync_total 13408
telemt_desync_full_logged_total 7550
telemt_desync_suppressed_total 5858
telemt_desync_frames_bucket_total{bucket="1_2"} 3057
telemt_desync_frames_bucket_total{bucket="3_10"} 5258
telemt_desync_frames_bucket_total{bucket="gt_10"} 5093
telemt_pool_swap_total 120
telemt_pool_force_close_total 3345
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 259
telemt_me_draining_writers_reap_progress_total 53487
telemt_me_writer_removed_unexpected_total 3765
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50510
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2863
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50142
telemt_me_writer_teardown_success_total{mode="normal"} 57292
telemt_me_writer_teardown_noop_total 53488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.820721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 259
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 3426
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 3276819
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 44175054883 (41.14 GB)
telemt_user_octets_to_client{user="hello"} 822288709213 (765.82 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 202428.9 (56h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16582947
telemt_connections_bad_total 1680862
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 404395
telemt_upstream_connect_attempt_total 91078
telemt_upstream_connect_success_total 90971
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3183
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1627
telemt_me_idle_close_by_peer_total 1625
telemt_me_route_drop_no_conn_total 14094377
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13169934
telemt_me_endpoint_quarantine_total 1370
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1530
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
telemt_me_writers_active_current 44
telemt_desync_total 54841
telemt_desync_full_logged_total 17513
telemt_desync_suppressed_total 37328
telemt_desync_frames_bucket_total{bucket="1_2"} 12230
telemt_desync_frames_bucket_total{bucket="3_10"} 21470
telemt_desync_frames_bucket_total{bucket="gt_10"} 21141
telemt_pool_swap_total 219
telemt_pool_force_close_total 7046
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1091
telemt_me_draining_writers_reap_progress_total 69980
telemt_me_writer_removed_unexpected_total 1562
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62934
telemt_me_writer_teardown_success_total{mode="normal"} 70826
telemt_me_writer_teardown_noop_total 70033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.474702
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1091
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 13169823
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 199547996869 (185.84 GB)
telemt_user_octets_to_client{user="hello"} 3569382343631 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 202430.4 (56h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12110799
telemt_connections_bad_total 1281946
telemt_connections_current 869
telemt_connections_me_current 869
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 350506
telemt_upstream_connect_attempt_total 105415
telemt_upstream_connect_success_total 104005
telemt_upstream_connect_fail_total 897
telemt_upstream_connect_attempts_per_request{bucket="1"} 104902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 897
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4648
telemt_me_reconnect_success_total 1998
telemt_me_reader_eof_total 1857
telemt_me_idle_close_by_peer_total 1857
telemt_me_route_drop_no_conn_total 4597659
telemt_me_route_drop_channel_closed_total 503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8961030
telemt_me_endpoint_quarantine_total 1380
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1549
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
telemt_desync_total 39380
telemt_desync_full_logged_total 13257
telemt_desync_suppressed_total 26123
telemt_desync_frames_bucket_total{bucket="1_2"} 9758
telemt_desync_frames_bucket_total{bucket="3_10"} 15140
telemt_desync_frames_bucket_total{bucket="gt_10"} 14482
telemt_pool_swap_total 216
telemt_pool_force_close_total 6391
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 68048
telemt_me_writer_removed_unexpected_total 1889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5879
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61657
telemt_me_writer_teardown_success_total{mode="normal"} 69798
telemt_me_writer_teardown_noop_total 68073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.605078
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1704
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8898673
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 219294109868 (204.23 GB)
telemt_user_octets_to_client{user="hello"} 4011555975847 (3.65 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 202394.6 (56h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11258543
telemt_connections_bad_total 1027571
telemt_connections_current 1074
telemt_connections_me_current 1074
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 351276
telemt_upstream_connect_attempt_total 89805
telemt_upstream_connect_success_total 88231
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5876
telemt_me_reconnect_success_total 2464
telemt_me_reader_eof_total 2211
telemt_me_idle_close_by_peer_total 2210
telemt_me_route_drop_no_conn_total 5366498
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8472711
telemt_me_endpoint_quarantine_total 1429
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1509
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38568
telemt_desync_full_logged_total 12797
telemt_desync_suppressed_total 25771
telemt_desync_frames_bucket_total{bucket="1_2"} 9742
telemt_desync_frames_bucket_total{bucket="3_10"} 14767
telemt_desync_frames_bucket_total{bucket="gt_10"} 14059
telemt_pool_swap_total 212
telemt_pool_force_close_total 6278
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 759
telemt_me_draining_writers_reap_progress_total 68618
telemt_me_writer_removed_unexpected_total 2357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6708
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62340
telemt_me_writer_teardown_success_total{mode="normal"} 70911
telemt_me_writer_teardown_noop_total 68689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.946617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 759
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8464585
telemt_user_connections_current{user="hello"} 1074
telemt_user_octets_from_client{user="hello"} 193731373431 (180.43 GB)
telemt_user_octets_to_client{user="hello"} 3513913706757 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72674.5 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11552518
telemt_connections_bad_total 679040
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 306933
telemt_upstream_connect_attempt_total 65117
telemt_upstream_connect_success_total 61686
telemt_upstream_connect_fail_total 2213
telemt_upstream_connect_attempts_per_request{bucket="1"} 63899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6035
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2213
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8289
telemt_me_reconnect_success_total 1480
telemt_me_reader_eof_total 949
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 25348796
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9571633
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 103
telemt_me_single_endpoint_outage_exit_total 103
telemt_me_single_endpoint_outage_reconnect_attempt_total 201
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 201
telemt_me_single_endpoint_shadow_rotate_total 584
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
telemt_desync_total 17097
telemt_desync_full_logged_total 4736
telemt_desync_suppressed_total 12361
telemt_desync_frames_bucket_total{bucket="1_2"} 3300
telemt_desync_frames_bucket_total{bucket="3_10"} 6989
telemt_desync_frames_bucket_total{bucket="gt_10"} 6808
telemt_pool_swap_total 75
telemt_pool_force_close_total 2341
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 518
telemt_me_draining_writers_reap_progress_total 24051
telemt_me_writer_removed_unexpected_total 1343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21710
telemt_me_writer_teardown_success_total{mode="normal"} 25345
telemt_me_writer_teardown_noop_total 24070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49415
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.648694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49415
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 518
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9598049
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 90051683630 (83.87 GB)
telemt_user_octets_to_client{user="hello"} 694896394201 (647.17 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 202401.2 (56h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11218456
telemt_connections_bad_total 990051
telemt_connections_current 1196
telemt_connections_me_current 1196
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 247863
telemt_upstream_connect_attempt_total 118725
telemt_upstream_connect_success_total 117492
telemt_upstream_connect_fail_total 1056
telemt_upstream_connect_attempts_per_request{bucket="1"} 118548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1056
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73470
telemt_me_reconnect_success_total 3240
telemt_me_reader_eof_total 2935
telemt_me_idle_close_by_peer_total 2932
telemt_me_route_drop_no_conn_total 5303522
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8831953
telemt_me_endpoint_quarantine_total 1372
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1539
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
telemt_me_writers_active_current 48
telemt_desync_total 47089
telemt_desync_full_logged_total 16184
telemt_desync_suppressed_total 30905
telemt_desync_frames_bucket_total{bucket="1_2"} 9556
telemt_desync_frames_bucket_total{bucket="3_10"} 18062
telemt_desync_frames_bucket_total{bucket="gt_10"} 19471
telemt_pool_swap_total 208
telemt_pool_force_close_total 6007
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 72680
telemt_me_writer_removed_unexpected_total 2953
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7253
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68426
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5258
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66673
telemt_me_writer_teardown_success_total{mode="normal"} 75679
telemt_me_writer_teardown_noop_total 72681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148360
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.353939
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148360
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 4320
telemt_me_writer_restored_same_endpoint_total 2730
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8834693
telemt_user_connections_current{user="hello"} 1196
telemt_user_octets_from_client{user="hello"} 198471201701 (184.84 GB)
telemt_user_octets_to_client{user="hello"} 3377804355828 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 139237.5 (38h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11974522
telemt_connections_bad_total 492481
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4831576
telemt_upstream_connect_attempt_total 67659
telemt_upstream_connect_success_total 67179
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 67646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_reconnect_attempts_total 49261
telemt_me_reconnect_success_total 1942
telemt_me_reader_eof_total 1624
telemt_me_idle_close_by_peer_total 1623
telemt_me_route_drop_no_conn_total 4127752
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5755776
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32392
telemt_desync_full_logged_total 11066
telemt_desync_suppressed_total 21326
telemt_desync_frames_bucket_total{bucket="1_2"} 6498
telemt_desync_frames_bucket_total{bucket="3_10"} 12760
telemt_desync_frames_bucket_total{bucket="gt_10"} 13134
telemt_pool_swap_total 148
telemt_pool_force_close_total 4202
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 52602
telemt_me_writer_removed_unexpected_total 1664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50166
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48400
telemt_me_writer_teardown_success_total{mode="normal"} 54320
telemt_me_writer_teardown_noop_total 52609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.807209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 2749
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5747746
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 121343750276 (113.01 GB)
telemt_user_octets_to_client{user="hello"} 2239235576994 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 120208.0 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1651604
telemt_connections_bad_total 37201
telemt_connections_current 823
telemt_connections_me_current 823
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34454
telemt_upstream_connect_attempt_total 56774
telemt_upstream_connect_success_total 56598
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 830
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2456
telemt_me_reconnect_success_total 999
telemt_me_reader_eof_total 994
telemt_me_idle_close_by_peer_total 994
telemt_me_route_drop_no_conn_total 550943
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1467968
telemt_me_endpoint_quarantine_total 1019
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 994
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
telemt_desync_total 10211
telemt_desync_full_logged_total 2878
telemt_desync_suppressed_total 7333
telemt_desync_frames_bucket_total{bucket="1_2"} 3219
telemt_desync_frames_bucket_total{bucket="3_10"} 3849
telemt_desync_frames_bucket_total{bucket="gt_10"} 3143
telemt_pool_swap_total 130
telemt_pool_force_close_total 3276
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 48387
telemt_me_writer_removed_unexpected_total 957
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3655
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45111
telemt_me_writer_teardown_success_total{mode="normal"} 49388
telemt_me_writer_teardown_noop_total 48391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.572259
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1463595
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 27209313569 (25.34 GB)
telemt_user_octets_to_client{user="hello"} 606907094519 (565.23 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 202406.0 (56h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13507159
telemt_connections_bad_total 1630437
telemt_connections_current 1216
telemt_connections_me_current 1216
telemt_handshake_timeouts_total 395598
telemt_upstream_connect_attempt_total 81511
telemt_upstream_connect_success_total 81150
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 81374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3173
telemt_me_reconnect_success_total 1605
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 4515510
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10183408
telemt_me_endpoint_quarantine_total 1490
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1537
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 42713
telemt_desync_full_logged_total 13943
telemt_desync_suppressed_total 28770
telemt_desync_frames_bucket_total{bucket="1_2"} 10399
telemt_desync_frames_bucket_total{bucket="3_10"} 15677
telemt_desync_frames_bucket_total{bucket="gt_10"} 16637
telemt_pool_swap_total 224
telemt_pool_force_close_total 5857
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 698
telemt_me_draining_writers_reap_progress_total 73800
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67943
telemt_me_writer_teardown_success_total{mode="normal"} 75386
telemt_me_writer_teardown_noop_total 73802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.949627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 698
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10149878
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 196383655632 (182.90 GB)
telemt_user_octets_to_client{user="hello"} 4523440807764 (4.11 TB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 202402.7 (56h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11825644
telemt_connections_bad_total 1385575
telemt_connections_current 1096
telemt_connections_me_current 1096
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 318390
telemt_upstream_connect_attempt_total 109365
telemt_upstream_connect_success_total 108423
telemt_upstream_connect_fail_total 734
telemt_upstream_connect_attempts_per_request{bucket="1"} 109157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 734
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11010
telemt_me_reconnect_success_total 2741
telemt_me_reader_eof_total 2542
telemt_me_idle_close_by_peer_total 2541
telemt_me_seq_mismatch_total 106
telemt_me_route_drop_no_conn_total 5682785
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9100587
telemt_me_endpoint_quarantine_total 1663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1542
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 42394
telemt_desync_full_logged_total 13645
telemt_desync_suppressed_total 28749
telemt_desync_frames_bucket_total{bucket="1_2"} 11020
telemt_desync_frames_bucket_total{bucket="3_10"} 15562
telemt_desync_frames_bucket_total{bucket="gt_10"} 15812
telemt_pool_swap_total 214
telemt_pool_force_close_total 5618
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 74134
telemt_me_writer_removed_unexpected_total 2577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69736
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68516
telemt_me_writer_teardown_success_total{mode="normal"} 76811
telemt_me_writer_teardown_noop_total 74139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150950
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.652163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150950
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 429
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_restored_fallback_total 141
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 9105059
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 158851150564 (147.94 GB)
telemt_user_octets_to_client{user="hello"} 3564786035250 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 154
```