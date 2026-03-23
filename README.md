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

# Server Metrics 2026-03-23 03:18:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 108703.3 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3715487
telemt_connections_bad_total 357945
telemt_connections_current 1043
telemt_connections_me_current 1043
telemt_handshake_timeouts_total 120290
telemt_upstream_connect_attempt_total 40553
telemt_upstream_connect_success_total 40552
telemt_upstream_connect_attempts_per_request{bucket="1"} 40552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1435
telemt_me_reconnect_success_total 635
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 3011813
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3035334
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 771
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 848
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 13050
telemt_desync_full_logged_total 4146
telemt_desync_suppressed_total 8904
telemt_desync_frames_bucket_total{bucket="1_2"} 3462
telemt_desync_frames_bucket_total{bucket="3_10"} 4769
telemt_desync_frames_bucket_total{bucket="gt_10"} 4819
telemt_pool_swap_total 120
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 37125
telemt_me_writer_removed_unexpected_total 629
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34760
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3606
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33463
telemt_me_writer_teardown_success_total{mode="normal"} 37402
telemt_me_writer_teardown_noop_total 37136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74538
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.601276
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74538
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3024213
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 42898694748 (39.95 GB)
telemt_user_octets_to_client{user="hello"} 824029673908 (767.44 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 122069.2 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4046541
telemt_connections_bad_total 373301
telemt_connections_current 461
telemt_connections_me_current 461
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101804
telemt_upstream_connect_attempt_total 76885
telemt_upstream_connect_success_total 75964
telemt_upstream_connect_fail_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 76778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 814
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10512
telemt_me_reconnect_success_total 3745
telemt_me_reader_eof_total 3726
telemt_me_idle_close_by_peer_total 3726
telemt_me_route_drop_no_conn_total 3647541
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3214302
telemt_me_endpoint_quarantine_total 990
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 961
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13110
telemt_desync_full_logged_total 7363
telemt_desync_suppressed_total 5747
telemt_desync_frames_bucket_total{bucket="1_2"} 2983
telemt_desync_frames_bucket_total{bucket="3_10"} 5141
telemt_desync_frames_bucket_total{bucket="gt_10"} 4986
telemt_pool_swap_total 115
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50814
telemt_me_writer_removed_unexpected_total 3651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47614
telemt_me_writer_teardown_success_total{mode="normal"} 54503
telemt_me_writer_teardown_noop_total 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.687925
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 265
telemt_me_writer_restored_same_endpoint_total 3318
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 3228783
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 43384400455 (40.40 GB)
telemt_user_octets_to_client{user="hello"} 802310333897 (747.21 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 196929.1 (54h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16451415
telemt_connections_bad_total 1669834
telemt_connections_current 1088
telemt_connections_me_current 1088
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399830
telemt_upstream_connect_attempt_total 88705
telemt_upstream_connect_success_total 88598
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3061
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1584
telemt_me_idle_close_by_peer_total 1582
telemt_me_route_drop_no_conn_total 14063424
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13059062
telemt_me_endpoint_quarantine_total 1323
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1486
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 54248
telemt_desync_full_logged_total 17282
telemt_desync_suppressed_total 36966
telemt_desync_frames_bucket_total{bucket="1_2"} 12102
telemt_desync_frames_bucket_total{bucket="3_10"} 21193
telemt_desync_frames_bucket_total{bucket="gt_10"} 20953
telemt_pool_swap_total 213
telemt_pool_force_close_total 6903
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1072
telemt_me_draining_writers_reap_progress_total 67803
telemt_me_writer_removed_unexpected_total 1522
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5713
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60900
telemt_me_writer_teardown_success_total{mode="normal"} 68606
telemt_me_writer_teardown_noop_total 67856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136462
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.012053
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136462
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1072
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1416
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 13059018
telemt_user_connections_current{user="hello"} 1088
telemt_user_octets_from_client{user="hello"} 198028814529 (184.43 GB)
telemt_user_octets_to_client{user="hello"} 3523756496155 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 196930.4 (54h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11991049
telemt_connections_bad_total 1259767
telemt_connections_current 717
telemt_connections_me_current 717
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345853
telemt_upstream_connect_attempt_total 102982
telemt_upstream_connect_success_total 101644
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 102529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4534
telemt_me_reconnect_success_total 1949
telemt_me_reader_eof_total 1815
telemt_me_idle_close_by_peer_total 1815
telemt_me_route_drop_no_conn_total 4569291
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8883491
telemt_me_endpoint_quarantine_total 1339
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1506
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39121
telemt_desync_full_logged_total 13178
telemt_desync_suppressed_total 25943
telemt_desync_frames_bucket_total{bucket="1_2"} 9686
telemt_desync_frames_bucket_total{bucket="3_10"} 15029
telemt_desync_frames_bucket_total{bucket="gt_10"} 14406
telemt_pool_swap_total 210
telemt_pool_force_close_total 6251
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 65911
telemt_me_writer_removed_unexpected_total 1842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5804
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59660
telemt_me_writer_teardown_success_total{mode="normal"} 67612
telemt_me_writer_teardown_noop_total 65936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133548
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.554839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133548
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 1667
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 8821195
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 218422648596 (203.42 GB)
telemt_user_octets_to_client{user="hello"} 3984416984959 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 196894.6 (54h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11143502
telemt_connections_bad_total 998105
telemt_connections_current 577
telemt_connections_me_current 577
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346577
telemt_upstream_connect_attempt_total 87415
telemt_upstream_connect_success_total 85849
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5820
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2170
telemt_me_idle_close_by_peer_total 2169
telemt_me_route_drop_no_conn_total 5347927
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8408351
telemt_me_endpoint_quarantine_total 1385
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1466
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38331
telemt_desync_full_logged_total 12710
telemt_desync_suppressed_total 25621
telemt_desync_frames_bucket_total{bucket="1_2"} 9683
telemt_desync_frames_bucket_total{bucket="3_10"} 14679
telemt_desync_frames_bucket_total{bucket="gt_10"} 13969
telemt_pool_swap_total 206
telemt_pool_force_close_total 6142
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 747
telemt_me_draining_writers_reap_progress_total 66449
telemt_me_writer_removed_unexpected_total 2318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6538
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62163
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5571
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60307
telemt_me_writer_teardown_success_total{mode="normal"} 68701
telemt_me_writer_teardown_noop_total 66520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135221
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.878490
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135221
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 747
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8400248
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 193141286007 (179.88 GB)
telemt_user_octets_to_client{user="hello"} 3486490900849 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67174.5 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11382721
telemt_connections_bad_total 671533
telemt_connections_current 1210
telemt_connections_me_current 1210
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 290324
telemt_upstream_connect_attempt_total 61874
telemt_upstream_connect_success_total 58687
telemt_upstream_connect_fail_total 2059
telemt_upstream_connect_attempts_per_request{bucket="1"} 60746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6021
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2059
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7916
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 25312056
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9436891
telemt_me_endpoint_quarantine_total 504
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 538
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 16721
telemt_desync_full_logged_total 4589
telemt_desync_suppressed_total 12132
telemt_desync_frames_bucket_total{bucket="1_2"} 3183
telemt_desync_frames_bucket_total{bucket="3_10"} 6823
telemt_desync_frames_bucket_total{bucket="gt_10"} 6715
telemt_pool_swap_total 69
telemt_pool_force_close_total 2193
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 22088
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20429
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19895
telemt_me_writer_teardown_success_total{mode="normal"} 23267
telemt_me_writer_teardown_noop_total 22107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45374
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.061650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45374
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 885
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 9462699
telemt_user_connections_current{user="hello"} 1210
telemt_user_octets_from_client{user="hello"} 87995066850 (81.95 GB)
telemt_user_octets_to_client{user="hello"} 641818415526 (597.74 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 196901.0 (54h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11098084
telemt_connections_bad_total 967783
telemt_connections_current 866
telemt_connections_me_current 866
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244697
telemt_upstream_connect_attempt_total 116220
telemt_upstream_connect_success_total 115032
telemt_upstream_connect_fail_total 1013
telemt_upstream_connect_attempts_per_request{bucket="1"} 116045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1013
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73203
telemt_me_reconnect_success_total 3164
telemt_me_reader_eof_total 2863
telemt_me_idle_close_by_peer_total 2860
telemt_me_route_drop_no_conn_total 5278390
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8746616
telemt_me_endpoint_quarantine_total 1337
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1494
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
telemt_me_writers_active_current 47
telemt_desync_total 46602
telemt_desync_full_logged_total 15995
telemt_desync_suppressed_total 30607
telemt_desync_frames_bucket_total{bucket="1_2"} 9468
telemt_desync_frames_bucket_total{bucket="3_10"} 17842
telemt_desync_frames_bucket_total{bucket="gt_10"} 19292
telemt_pool_swap_total 202
telemt_pool_force_close_total 5860
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 70477
telemt_me_writer_removed_unexpected_total 2883
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7085
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5111
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64617
telemt_me_writer_teardown_success_total{mode="normal"} 73404
telemt_me_writer_teardown_noop_total 70478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.320286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2667
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8749477
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 196618499693 (183.12 GB)
telemt_user_octets_to_client{user="hello"} 3342509581928 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 133737.3 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11821692
telemt_connections_bad_total 484247
telemt_connections_current 782
telemt_connections_me_current 782
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4789347
telemt_upstream_connect_attempt_total 64982
telemt_upstream_connect_success_total 64513
telemt_upstream_connect_fail_total 456
telemt_upstream_connect_attempts_per_request{bucket="1"} 64969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 456
telemt_me_reconnect_attempts_total 49181
telemt_me_reconnect_success_total 1915
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1590
telemt_me_route_drop_no_conn_total 4106256
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5679711
telemt_me_endpoint_quarantine_total 919
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1032
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31892
telemt_desync_full_logged_total 10905
telemt_desync_suppressed_total 20987
telemt_desync_frames_bucket_total{bucket="1_2"} 6366
telemt_desync_frames_bucket_total{bucket="3_10"} 12583
telemt_desync_frames_bucket_total{bucket="gt_10"} 12943
telemt_pool_swap_total 142
telemt_pool_force_close_total 4067
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 50109
telemt_me_writer_removed_unexpected_total 1635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4035
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47759
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46042
telemt_me_writer_teardown_success_total{mode="normal"} 51794
telemt_me_writer_teardown_noop_total 50116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.757028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 2746
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5671780
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 120509959912 (112.23 GB)
telemt_user_octets_to_client{user="hello"} 2208707203322 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 114708.4 (31h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581139
telemt_connections_bad_total 36991
telemt_connections_current 543
telemt_connections_me_current 543
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32562
telemt_upstream_connect_attempt_total 54352
telemt_upstream_connect_success_total 54182
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 54323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 806
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 530890
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1405726
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 951
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9861
telemt_desync_full_logged_total 2789
telemt_desync_suppressed_total 7072
telemt_desync_frames_bucket_total{bucket="1_2"} 3069
telemt_desync_frames_bucket_total{bucket="3_10"} 3726
telemt_desync_frames_bucket_total{bucket="gt_10"} 3066
telemt_pool_swap_total 124
telemt_pool_force_close_total 3122
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 46231
telemt_me_writer_removed_unexpected_total 921
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43690
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3034
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43109
telemt_me_writer_teardown_success_total{mode="normal"} 47194
telemt_me_writer_teardown_noop_total 46235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.495997
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1401446
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 26526792853 (24.71 GB)
telemt_user_octets_to_client{user="hello"} 589985255899 (549.47 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 196905.6 (54h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13417661
telemt_connections_bad_total 1626971
telemt_connections_current 827
telemt_connections_me_current 827
telemt_handshake_timeouts_total 391605
telemt_upstream_connect_attempt_total 78863
telemt_upstream_connect_success_total 78508
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 78727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3085
telemt_me_reconnect_success_total 1560
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 4493709
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10104156
telemt_me_endpoint_quarantine_total 1439
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1493
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42385
telemt_desync_full_logged_total 13846
telemt_desync_suppressed_total 28539
telemt_desync_frames_bucket_total{bucket="1_2"} 10310
telemt_desync_frames_bucket_total{bucket="3_10"} 15569
telemt_desync_frames_bucket_total{bucket="gt_10"} 16506
telemt_pool_swap_total 218
telemt_pool_force_close_total 5726
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 686
telemt_me_draining_writers_reap_progress_total 71363
telemt_me_writer_removed_unexpected_total 1481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67364
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65637
telemt_me_writer_teardown_success_total{mode="normal"} 72899
telemt_me_writer_teardown_noop_total 71365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.857434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 686
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1373
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10070783
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 195274155312 (181.86 GB)
telemt_user_octets_to_client{user="hello"} 4478465839464 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 196902.1 (54h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11725860
telemt_connections_bad_total 1371840
telemt_connections_current 676
telemt_connections_me_current 676
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313975
telemt_upstream_connect_attempt_total 106528
telemt_upstream_connect_success_total 105611
telemt_upstream_connect_fail_total 709
telemt_upstream_connect_attempts_per_request{bucket="1"} 106320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 709
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10763
telemt_me_reconnect_success_total 2672
telemt_me_reader_eof_total 2481
telemt_me_idle_close_by_peer_total 2480
telemt_me_seq_mismatch_total 103
telemt_me_route_drop_no_conn_total 5661946
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9022069
telemt_me_endpoint_quarantine_total 1612
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1498
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
telemt_me_writers_active_current 44
telemt_desync_total 42114
telemt_desync_full_logged_total 13561
telemt_desync_suppressed_total 28553
telemt_desync_frames_bucket_total{bucket="1_2"} 10937
telemt_desync_frames_bucket_total{bucket="3_10"} 15479
telemt_desync_frames_bucket_total{bucket="gt_10"} 15698
telemt_pool_swap_total 208
telemt_pool_force_close_total 5495
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71556
telemt_me_writer_removed_unexpected_total 2516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5024
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66061
telemt_me_writer_teardown_success_total{mode="normal"} 74169
telemt_me_writer_teardown_noop_total 71561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145730
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.572627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145730
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 419
telemt_me_writer_restored_same_endpoint_total 2139
telemt_me_writer_restored_fallback_total 139
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9026628
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 157894872008 (147.05 GB)
telemt_user_octets_to_client{user="hello"} 3521167169462 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 82
```