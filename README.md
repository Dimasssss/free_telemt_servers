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

# Server Metrics 2026-03-22 22:48:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 92528.5 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3340174
telemt_connections_bad_total 263319
telemt_connections_current 814
telemt_connections_me_current 814
telemt_handshake_timeouts_total 105542
telemt_upstream_connect_attempt_total 34022
telemt_upstream_connect_success_total 34021
telemt_upstream_connect_attempts_per_request{bucket="1"} 34021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1346
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 572
telemt_me_idle_close_by_peer_total 572
telemt_me_route_drop_no_conn_total 2963830
telemt_me_route_drop_channel_closed_total 1228
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2796395
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 631
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 721
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 11948
telemt_desync_full_logged_total 3744
telemt_desync_suppressed_total 8204
telemt_desync_frames_bucket_total{bucket="1_2"} 3227
telemt_desync_frames_bucket_total{bucket="3_10"} 4367
telemt_desync_frames_bucket_total{bucket="gt_10"} 4354
telemt_pool_swap_total 102
telemt_pool_force_close_total 3173
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 31152
telemt_me_writer_removed_unexpected_total 552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29112
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3118
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27979
telemt_me_writer_teardown_success_total{mode="normal"} 31372
telemt_me_writer_teardown_noop_total 31163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62535
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.585819
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62535
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 495
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2785718
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 39913458036 (37.17 GB)
telemt_user_octets_to_client{user="hello"} 755858678464 (703.95 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 105894.8 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3953991
telemt_connections_bad_total 360377
telemt_connections_current 403
telemt_connections_me_current 403
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99868
telemt_upstream_connect_attempt_total 63774
telemt_upstream_connect_success_total 62993
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 63684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9456
telemt_me_reconnect_success_total 3458
telemt_me_reader_eof_total 3475
telemt_me_idle_close_by_peer_total 3475
telemt_me_route_drop_no_conn_total 3635761
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3144789
telemt_me_endpoint_quarantine_total 786
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 819
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
telemt_me_writers_active_current 44
telemt_desync_total 12818
telemt_desync_full_logged_total 7186
telemt_desync_suppressed_total 5632
telemt_desync_frames_bucket_total{bucket="1_2"} 2897
telemt_desync_frames_bucket_total{bucket="3_10"} 5030
telemt_desync_frames_bucket_total{bucket="gt_10"} 4891
telemt_pool_swap_total 97
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 242
telemt_me_draining_writers_reap_progress_total 42543
telemt_me_writer_removed_unexpected_total 3411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40158
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39584
telemt_me_writer_teardown_success_total{mode="normal"} 45981
telemt_me_writer_teardown_noop_total 42544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.512345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 242
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 3127
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 3155429
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 42696742791 (39.76 GB)
telemt_user_octets_to_client{user="hello"} 779447279810 (725.92 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 180754.6 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16214795
telemt_connections_bad_total 1610132
telemt_connections_current 1064
telemt_connections_me_current 1064
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396242
telemt_upstream_connect_attempt_total 80299
telemt_upstream_connect_success_total 80199
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 80216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2912
telemt_me_reconnect_success_total 1509
telemt_me_reader_eof_total 1454
telemt_me_idle_close_by_peer_total 1452
telemt_me_route_drop_no_conn_total 14031399
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12896438
telemt_me_endpoint_quarantine_total 1168
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1352
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53325
telemt_desync_full_logged_total 16905
telemt_desync_suppressed_total 36420
telemt_desync_frames_bucket_total{bucket="1_2"} 11853
telemt_desync_frames_bucket_total{bucket="3_10"} 20760
telemt_desync_frames_bucket_total{bucket="gt_10"} 20712
telemt_pool_swap_total 195
telemt_pool_force_close_total 6509
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1046
telemt_me_draining_writers_reap_progress_total 60081
telemt_me_writer_removed_unexpected_total 1403
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6039
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53572
telemt_me_writer_teardown_success_total{mode="normal"} 60754
telemt_me_writer_teardown_noop_total 60134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120888
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.940269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120888
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1046
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1304
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12896670
telemt_user_connections_current{user="hello"} 1064
telemt_user_octets_from_client{user="hello"} 190064968333 (177.01 GB)
telemt_user_octets_to_client{user="hello"} 3464711673779 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 180756.0 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11771529
telemt_connections_bad_total 1210878
telemt_connections_current 699
telemt_connections_me_current 699
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344010
telemt_upstream_connect_attempt_total 94756
telemt_upstream_connect_success_total 93445
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 94309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4323
telemt_me_reconnect_success_total 1812
telemt_me_reader_eof_total 1673
telemt_me_idle_close_by_peer_total 1673
telemt_me_route_drop_no_conn_total 4544463
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8752264
telemt_me_endpoint_quarantine_total 1172
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1373
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38612
telemt_desync_full_logged_total 12990
telemt_desync_suppressed_total 25622
telemt_desync_frames_bucket_total{bucket="1_2"} 9540
telemt_desync_frames_bucket_total{bucket="3_10"} 14841
telemt_desync_frames_bucket_total{bucket="gt_10"} 14231
telemt_pool_swap_total 192
telemt_pool_force_close_total 5878
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58417
telemt_me_writer_removed_unexpected_total 1708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5366
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52539
telemt_me_writer_teardown_success_total{mode="normal"} 59976
telemt_me_writer_teardown_noop_total 58442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118418
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.264176
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118418
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1544
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8690088
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 217343558220 (202.42 GB)
telemt_user_octets_to_client{user="hello"} 3936963622107 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 180720.0 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10972099
telemt_connections_bad_total 956314
telemt_connections_current 556
telemt_connections_me_current 556
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345019
telemt_upstream_connect_attempt_total 78819
telemt_upstream_connect_success_total 77276
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 77481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5644
telemt_me_reconnect_success_total 2294
telemt_me_reader_eof_total 2034
telemt_me_idle_close_by_peer_total 2033
telemt_me_route_drop_no_conn_total 5326684
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8303535
telemt_me_endpoint_quarantine_total 1248
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1330
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37896
telemt_desync_full_logged_total 12566
telemt_desync_suppressed_total 25330
telemt_desync_frames_bucket_total{bucket="1_2"} 9570
telemt_desync_frames_bucket_total{bucket="3_10"} 14494
telemt_desync_frames_bucket_total{bucket="gt_10"} 13832
telemt_pool_swap_total 188
telemt_pool_force_close_total 5794
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 733
telemt_me_draining_writers_reap_progress_total 58639
telemt_me_writer_removed_unexpected_total 2188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52845
telemt_me_writer_teardown_success_total{mode="normal"} 60755
telemt_me_writer_teardown_noop_total 58710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119465
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.618157
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119465
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 733
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8295523
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 192168411697 (178.97 GB)
telemt_user_octets_to_client{user="hello"} 3450069134305 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51000.1 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11106788
telemt_connections_bad_total 667214
telemt_connections_current 1095
telemt_connections_me_current 1095
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 254931
telemt_upstream_connect_attempt_total 53252
telemt_upstream_connect_success_total 50481
telemt_upstream_connect_fail_total 1885
telemt_upstream_connect_attempts_per_request{bucket="1"} 52366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1885
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7282
telemt_me_reconnect_success_total 1106
telemt_me_reader_eof_total 677
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 25267740
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9225563
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 406
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 15864
telemt_desync_full_logged_total 4232
telemt_desync_suppressed_total 11632
telemt_desync_frames_bucket_total{bucket="1_2"} 3030
telemt_desync_frames_bucket_total{bucket="3_10"} 6410
telemt_desync_frames_bucket_total{bucket="gt_10"} 6424
telemt_pool_swap_total 52
telemt_pool_force_close_total 1792
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 462
telemt_me_draining_writers_reap_progress_total 15181
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13930
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13389
telemt_me_writer_teardown_success_total{mode="normal"} 16128
telemt_me_writer_teardown_noop_total 15200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.671308
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 462
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 9251074
telemt_user_connections_current{user="hello"} 1095
telemt_user_octets_from_client{user="hello"} 86037865314 (80.13 GB)
telemt_user_octets_to_client{user="hello"} 574991915489 (535.50 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 180726.7 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10900799
telemt_connections_bad_total 927911
telemt_connections_current 874
telemt_connections_me_current 874
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239547
telemt_upstream_connect_attempt_total 107622
telemt_upstream_connect_success_total 106501
telemt_upstream_connect_fail_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 107450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 949
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72740
telemt_me_reconnect_success_total 2974
telemt_me_reader_eof_total 2671
telemt_me_idle_close_by_peer_total 2669
telemt_me_route_drop_no_conn_total 5246887
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8609624
telemt_me_endpoint_quarantine_total 1191
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 45947
telemt_desync_full_logged_total 15717
telemt_desync_suppressed_total 30230
telemt_desync_frames_bucket_total{bucket="1_2"} 9316
telemt_desync_frames_bucket_total{bucket="3_10"} 17586
telemt_desync_frames_bucket_total{bucket="gt_10"} 19045
telemt_pool_swap_total 184
telemt_pool_force_close_total 5483
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 62668
telemt_me_writer_removed_unexpected_total 2703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6576
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4734
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57185
telemt_me_writer_teardown_success_total{mode="normal"} 65403
telemt_me_writer_teardown_noop_total 62669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.185910
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 4296
telemt_me_writer_restored_same_endpoint_total 2512
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8612701
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 193932766565 (180.61 GB)
telemt_user_octets_to_client{user="hello"} 3288512048136 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 117562.9 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11571343
telemt_connections_bad_total 462555
telemt_connections_current 684
telemt_connections_me_current 684
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4741549
telemt_upstream_connect_attempt_total 55748
telemt_upstream_connect_success_total 55338
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 55737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_reconnect_attempts_total 48724
telemt_me_reconnect_success_total 1741
telemt_me_reader_eof_total 1405
telemt_me_idle_close_by_peer_total 1404
telemt_me_route_drop_no_conn_total 4075722
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5565861
telemt_me_endpoint_quarantine_total 767
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 894
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31302
telemt_desync_full_logged_total 10656
telemt_desync_suppressed_total 20646
telemt_desync_frames_bucket_total{bucket="1_2"} 6212
telemt_desync_frames_bucket_total{bucket="3_10"} 12354
telemt_desync_frames_bucket_total{bucket="gt_10"} 12736
telemt_pool_swap_total 124
telemt_pool_force_close_total 3726
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 41695
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3560
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39634
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3285
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37969
telemt_me_writer_teardown_success_total{mode="normal"} 43194
telemt_me_writer_teardown_noop_total 41702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84896
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.637275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84896
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1545
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5558477
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 118642982344 (110.49 GB)
telemt_user_octets_to_client{user="hello"} 2149474434810 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 98533.9 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1469099
telemt_connections_bad_total 36404
telemt_connections_current 544
telemt_connections_me_current 544
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29286
telemt_upstream_connect_attempt_total 46096
telemt_upstream_connect_success_total 45951
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 46068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 769
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 506751
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1303878
telemt_me_endpoint_quarantine_total 797
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 812
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
telemt_me_writers_active_current 45
telemt_desync_total 8233
telemt_desync_full_logged_total 2487
telemt_desync_suppressed_total 5746
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3185
telemt_desync_frames_bucket_total{bucket="gt_10"} 2986
telemt_pool_swap_total 106
telemt_pool_force_close_total 2757
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 38661
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2669
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35904
telemt_me_writer_teardown_success_total{mode="normal"} 39514
telemt_me_writer_teardown_noop_total 38665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.015954
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 735
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1299765
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 25547346833 (23.79 GB)
telemt_user_octets_to_client{user="hello"} 555130362387 (517.01 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 180731.3 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13223777
telemt_connections_bad_total 1569017
telemt_connections_current 753
telemt_connections_me_current 753
telemt_handshake_timeouts_total 380584
telemt_upstream_connect_attempt_total 69357
telemt_upstream_connect_success_total 69017
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 69221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2711
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1374
telemt_me_idle_close_by_peer_total 1374
telemt_me_route_drop_no_conn_total 4473148
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9995472
telemt_me_endpoint_quarantine_total 1237
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 41
telemt_desync_total 41770
telemt_desync_full_logged_total 13634
telemt_desync_suppressed_total 28136
telemt_desync_frames_bucket_total{bucket="1_2"} 10039
telemt_desync_frames_bucket_total{bucket="3_10"} 15368
telemt_desync_frames_bucket_total{bucket="gt_10"} 16363
telemt_pool_swap_total 200
telemt_pool_force_close_total 5440
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 62583
telemt_me_writer_removed_unexpected_total 1319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58921
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57143
telemt_me_writer_teardown_success_total{mode="normal"} 63947
telemt_me_writer_teardown_noop_total 62585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.617937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1224
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 9962238
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 194208741012 (180.87 GB)
telemt_user_octets_to_client{user="hello"} 4417090886448 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 180727.9 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11520289
telemt_connections_bad_total 1316973
telemt_connections_current 654
telemt_connections_me_current 654
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 305711
telemt_upstream_connect_attempt_total 95925
telemt_upstream_connect_success_total 95073
telemt_upstream_connect_fail_total 645
telemt_upstream_connect_attempts_per_request{bucket="1"} 95718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 645
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10113
telemt_me_reconnect_success_total 2464
telemt_me_reader_eof_total 2296
telemt_me_idle_close_by_peer_total 2295
telemt_me_seq_mismatch_total 88
telemt_me_route_drop_no_conn_total 5633585
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8897525
telemt_me_endpoint_quarantine_total 1409
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1360
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 41407
telemt_desync_full_logged_total 13288
telemt_desync_suppressed_total 28119
telemt_desync_frames_bucket_total{bucket="1_2"} 10642
telemt_desync_frames_bucket_total{bucket="3_10"} 15233
telemt_desync_frames_bucket_total{bucket="gt_10"} 15532
telemt_pool_swap_total 190
telemt_pool_force_close_total 5231
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 62427
telemt_me_writer_removed_unexpected_total 2333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6385
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58455
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4760
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57196
telemt_me_writer_teardown_success_total{mode="normal"} 64840
telemt_me_writer_teardown_noop_total 62432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127272
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.329065
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127272
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1997
telemt_me_writer_restored_fallback_total 120
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8902921
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 156885107193 (146.11 GB)
telemt_user_octets_to_client{user="hello"} 3465925523319 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 64
```