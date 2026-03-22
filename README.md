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

# Server Metrics 2026-03-22 16:49:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71011.7 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2528060
telemt_connections_bad_total 135819
telemt_connections_current 1639
telemt_connections_me_current 1639
telemt_handshake_timeouts_total 89039
telemt_upstream_connect_attempt_total 26152
telemt_upstream_connect_success_total 26151
telemt_upstream_connect_attempts_per_request{bucket="1"} 26151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1043
telemt_me_reconnect_success_total 449
telemt_me_reader_eof_total 451
telemt_me_idle_close_by_peer_total 451
telemt_me_route_drop_no_conn_total 2040689
telemt_me_route_drop_channel_closed_total 851
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2154860
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 554
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10240
telemt_desync_full_logged_total 3225
telemt_desync_suppressed_total 7015
telemt_desync_frames_bucket_total{bucket="1_2"} 2733
telemt_desync_frames_bucket_total{bucket="3_10"} 3827
telemt_desync_frames_bucket_total{bucket="gt_10"} 3680
telemt_pool_swap_total 78
telemt_pool_force_close_total 2425
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 23889
telemt_me_writer_removed_unexpected_total 437
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22363
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2374
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21464
telemt_me_writer_teardown_success_total{mode="normal"} 24103
telemt_me_writer_teardown_noop_total 23895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 226.002236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2151365
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 32353652756 (30.13 GB)
telemt_user_octets_to_client{user="hello"} 572992914704 (533.64 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 84377.6 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3626549
telemt_connections_bad_total 329330
telemt_connections_current 1103
telemt_connections_me_current 1103
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 90380
telemt_upstream_connect_attempt_total 52788
telemt_upstream_connect_success_total 52148
telemt_upstream_connect_fail_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 52716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 568
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6105
telemt_me_reconnect_success_total 2211
telemt_me_reader_eof_total 2150
telemt_me_idle_close_by_peer_total 2150
telemt_me_route_drop_no_conn_total 3539261
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2875218
telemt_me_endpoint_quarantine_total 672
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 651
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 11270
telemt_desync_full_logged_total 6286
telemt_desync_suppressed_total 4984
telemt_desync_frames_bucket_total{bucket="1_2"} 2620
telemt_desync_frames_bucket_total{bucket="3_10"} 4419
telemt_desync_frames_bucket_total{bucket="gt_10"} 4231
telemt_pool_swap_total 79
telemt_pool_force_close_total 2375
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 199
telemt_me_draining_writers_reap_progress_total 33672
telemt_me_writer_removed_unexpected_total 2103
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4024
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31759
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2017
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31297
telemt_me_writer_teardown_success_total{mode="normal"} 35783
telemt_me_writer_teardown_noop_total 33672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69455
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.018280
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69455
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 199
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 1918
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 2886475
telemt_user_connections_current{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 36136966831 (33.66 GB)
telemt_user_octets_to_client{user="hello"} 648971126114 (604.40 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 650
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 159237.5 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15392815
telemt_connections_bad_total 1441539
telemt_connections_current 2692
telemt_connections_me_current 2692
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 375283
telemt_upstream_connect_attempt_total 71793
telemt_upstream_connect_success_total 71697
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2673
telemt_me_reconnect_success_total 1364
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1301
telemt_me_route_drop_no_conn_total 13823769
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12295768
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1186
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
telemt_me_writers_active_current 45
telemt_desync_total 50140
telemt_desync_full_logged_total 15746
telemt_desync_suppressed_total 34394
telemt_desync_frames_bucket_total{bucket="1_2"} 11209
telemt_desync_frames_bucket_total{bucket="3_10"} 19585
telemt_desync_frames_bucket_total{bucket="gt_10"} 19346
telemt_pool_swap_total 171
telemt_pool_force_close_total 5823
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 941
telemt_me_draining_writers_reap_progress_total 52356
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4556
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48348
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46533
telemt_me_writer_teardown_success_total{mode="normal"} 52904
telemt_me_writer_teardown_noop_total 52406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.787960
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 941
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1171
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 12296892
telemt_user_connections_current{user="hello"} 2692
telemt_user_octets_from_client{user="hello"} 175691604665 (163.63 GB)
telemt_user_octets_to_client{user="hello"} 3186511409695 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1050
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 159238.8 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11106798
telemt_connections_bad_total 1079723
telemt_connections_current 1626
telemt_connections_me_current 1626
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 330035
telemt_upstream_connect_attempt_total 84003
telemt_upstream_connect_success_total 82846
telemt_upstream_connect_fail_total 833
telemt_upstream_connect_attempts_per_request{bucket="1"} 83679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 833
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3947
telemt_me_reconnect_success_total 1611
telemt_me_reader_eof_total 1483
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 4372304
telemt_me_route_drop_channel_closed_total 480
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8282631
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1203
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36813
telemt_desync_full_logged_total 12379
telemt_desync_suppressed_total 24434
telemt_desync_frames_bucket_total{bucket="1_2"} 9039
telemt_desync_frames_bucket_total{bucket="3_10"} 14184
telemt_desync_frames_bucket_total{bucket="gt_10"} 13590
telemt_pool_swap_total 169
telemt_pool_force_close_total 5241
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50649
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45408
telemt_me_writer_teardown_success_total{mode="normal"} 52021
telemt_me_writer_teardown_noop_total 50667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.279778
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1373
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8221257
telemt_user_connections_current{user="hello"} 1626
telemt_user_octets_from_client{user="hello"} 205518771113 (191.40 GB)
telemt_user_octets_to_client{user="hello"} 3705543598418 (3.37 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 159204.9 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10498000
telemt_connections_bad_total 904859
telemt_connections_current 1299
telemt_connections_me_current 1299
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 335818
telemt_upstream_connect_attempt_total 69171
telemt_upstream_connect_success_total 68200
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2085
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4726
telemt_me_reconnect_success_total 1908
telemt_me_reader_eof_total 1659
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 5144899
telemt_me_route_drop_channel_closed_total 361
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7921816
telemt_me_endpoint_quarantine_total 1090
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36246
telemt_desync_full_logged_total 12008
telemt_desync_suppressed_total 24238
telemt_desync_frames_bucket_total{bucket="1_2"} 9172
telemt_desync_frames_bucket_total{bucket="3_10"} 13852
telemt_desync_frames_bucket_total{bucket="gt_10"} 13222
telemt_pool_swap_total 166
telemt_pool_force_close_total 5191
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50976
telemt_me_writer_removed_unexpected_total 1800
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47581
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45785
telemt_me_writer_teardown_success_total{mode="normal"} 52689
telemt_me_writer_teardown_noop_total 51047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103736
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.787895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103736
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 1647
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 7914737
telemt_user_connections_current{user="hello"} 1299
telemt_user_octets_from_client{user="hello"} 182954604493 (170.39 GB)
telemt_user_octets_to_client{user="hello"} 3291408963097 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 529
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 29483.1 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10228221
telemt_connections_bad_total 624557
telemt_connections_current 2439
telemt_connections_me_current 2439
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 193467
telemt_upstream_connect_attempt_total 36284
telemt_upstream_connect_success_total 34479
telemt_upstream_connect_fail_total 1257
telemt_upstream_connect_attempts_per_request{bucket="1"} 35736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1257
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5903
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 24962524
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8512574
telemt_me_endpoint_quarantine_total 179
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 13317
telemt_desync_full_logged_total 3446
telemt_desync_suppressed_total 9871
telemt_desync_frames_bucket_total{bucket="1_2"} 2377
telemt_desync_frames_bucket_total{bucket="3_10"} 5414
telemt_desync_frames_bucket_total{bucket="gt_10"} 5526
telemt_pool_swap_total 28
telemt_pool_force_close_total 1097
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 8121
telemt_me_writer_removed_unexpected_total 625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1313
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 817
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7024
telemt_me_writer_teardown_success_total{mode="normal"} 8711
telemt_me_writer_teardown_noop_total 8126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.448056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8530630
telemt_user_connections_current{user="hello"} 2439
telemt_user_octets_from_client{user="hello"} 65197304518 (60.72 GB)
telemt_user_octets_to_client{user="hello"} 324091666672 (301.83 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 834
telemt_user_unique_ips_recent_window{user="hello"} 350
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 159209.6 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10293112
telemt_connections_bad_total 864493
telemt_connections_current 1877
telemt_connections_me_current 1877
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228648
telemt_upstream_connect_attempt_total 97949
telemt_upstream_connect_success_total 96936
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 97799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72049
telemt_me_reconnect_success_total 2631
telemt_me_reader_eof_total 2334
telemt_me_idle_close_by_peer_total 2332
telemt_me_route_drop_no_conn_total 5075869
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8117227
telemt_me_endpoint_quarantine_total 1073
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1185
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 42366
telemt_desync_full_logged_total 14456
telemt_desync_suppressed_total 27910
telemt_desync_frames_bucket_total{bucket="1_2"} 8602
telemt_desync_frames_bucket_total{bucket="3_10"} 16386
telemt_desync_frames_bucket_total{bucket="gt_10"} 17378
telemt_pool_swap_total 162
telemt_pool_force_close_total 4820
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 604
telemt_me_draining_writers_reap_progress_total 54117
telemt_me_writer_removed_unexpected_total 2377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5780
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50735
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4135
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49297
telemt_me_writer_teardown_success_total{mode="normal"} 56515
telemt_me_writer_teardown_noop_total 54118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.482780
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 604
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2203
telemt_me_writer_restored_fallback_total 45
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8121123
telemt_user_connections_current{user="hello"} 1877
telemt_user_octets_from_client{user="hello"} 183701963109 (171.09 GB)
telemt_user_octets_to_client{user="hello"} 3059177668108 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 726
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 96045.8 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10725580
telemt_connections_bad_total 403956
telemt_connections_current 1536
telemt_connections_me_current 1536
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4497516
telemt_upstream_connect_attempt_total 46171
telemt_upstream_connect_success_total 45835
telemt_upstream_connect_fail_total 327
telemt_upstream_connect_attempts_per_request{bucket="1"} 46162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 327
telemt_me_reconnect_attempts_total 48148
telemt_me_reconnect_success_total 1524
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 3929216
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5142155
telemt_me_endpoint_quarantine_total 623
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 722
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28273
telemt_desync_full_logged_total 9558
telemt_desync_suppressed_total 18715
telemt_desync_frames_bucket_total{bucket="1_2"} 5700
telemt_desync_frames_bucket_total{bucket="3_10"} 11151
telemt_desync_frames_bucket_total{bucket="gt_10"} 11422
telemt_pool_swap_total 101
telemt_pool_force_close_total 3106
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 33106
telemt_me_writer_removed_unexpected_total 1253
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31418
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2687
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30000
telemt_me_writer_teardown_success_total{mode="normal"} 34389
telemt_me_writer_teardown_noop_total 33113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67502
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.919722
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67502
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 2710
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5135628
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 110607338448 (103.01 GB)
telemt_user_octets_to_client{user="hello"} 1940969607134 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 77016.6 (21h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051242
telemt_connections_bad_total 15730
telemt_connections_current 1118
telemt_connections_me_current 1118
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20106
telemt_upstream_connect_attempt_total 37665
telemt_upstream_connect_success_total 37563
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 37644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 545
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 1730
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 367599
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935989
telemt_me_endpoint_quarantine_total 656
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5319
telemt_desync_full_logged_total 1627
telemt_desync_suppressed_total 3692
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 2105
telemt_desync_frames_bucket_total{bucket="gt_10"} 1972
telemt_pool_swap_total 82
telemt_pool_force_close_total 2085
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 31213
telemt_me_writer_removed_unexpected_total 673
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2416
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29496
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29128
telemt_me_writer_teardown_success_total{mode="normal"} 31912
telemt_me_writer_teardown_noop_total 31216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63128
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.768076
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63128
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 615
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 932513
telemt_user_connections_current{user="hello"} 1118
telemt_user_octets_from_client{user="hello"} 16720089513 (15.57 GB)
telemt_user_octets_to_client{user="hello"} 408463474307 (380.41 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 159214.1 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12567955
telemt_connections_bad_total 1456702
telemt_connections_current 1972
telemt_connections_me_current 1972
telemt_handshake_timeouts_total 347679
telemt_upstream_connect_attempt_total 59780
telemt_upstream_connect_success_total 59533
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 59715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 2350
telemt_me_reconnect_success_total 1245
telemt_me_reader_eof_total 1209
telemt_me_idle_close_by_peer_total 1209
telemt_me_route_drop_no_conn_total 4194286
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9505792
telemt_me_endpoint_quarantine_total 1070
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1188
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 39016
telemt_desync_full_logged_total 12735
telemt_desync_suppressed_total 26281
telemt_desync_frames_bucket_total{bucket="1_2"} 9282
telemt_desync_frames_bucket_total{bucket="3_10"} 14459
telemt_desync_frames_bucket_total{bucket="gt_10"} 15275
telemt_pool_swap_total 176
telemt_pool_force_close_total 4862
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 621
telemt_me_draining_writers_reap_progress_total 53823
telemt_me_writer_removed_unexpected_total 1162
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50599
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48961
telemt_me_writer_teardown_success_total{mode="normal"} 55018
telemt_me_writer_teardown_noop_total 53825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.264385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 621
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1089
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 9474986
telemt_user_connections_current{user="hello"} 1972
telemt_user_octets_from_client{user="hello"} 186017067248 (173.24 GB)
telemt_user_octets_to_client{user="hello"} 4185422256440 (3.81 TB)
telemt_user_unique_ips_current{user="hello"} 707
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 159212.5 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10895623
telemt_connections_bad_total 1216376
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 281140
telemt_upstream_connect_attempt_total 85600
telemt_upstream_connect_success_total 84928
telemt_upstream_connect_fail_total 561
telemt_upstream_connect_attempts_per_request{bucket="1"} 85489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 561
telemt_me_reconnect_attempts_total 9008
telemt_me_reconnect_success_total 2074
telemt_me_reader_eof_total 1933
telemt_me_idle_close_by_peer_total 1933
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5439089
telemt_me_route_drop_channel_closed_total 349
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8427389
telemt_me_endpoint_quarantine_total 1211
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1190
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 38431
telemt_desync_full_logged_total 12416
telemt_desync_suppressed_total 26015
telemt_desync_frames_bucket_total{bucket="1_2"} 9553
telemt_desync_frames_bucket_total{bucket="3_10"} 14316
telemt_desync_frames_bucket_total{bucket="gt_10"} 14562
telemt_pool_swap_total 168
telemt_pool_force_close_total 4699
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 53324
telemt_me_writer_removed_unexpected_total 1959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5513
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49839
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4260
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48625
telemt_me_writer_teardown_success_total{mode="normal"} 55352
telemt_me_writer_teardown_noop_total 53329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.607386
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1681
telemt_me_writer_restored_fallback_total 100
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 8433342
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 148459193321 (138.26 GB)
telemt_user_octets_to_client{user="hello"} 3223022818031 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 238
```