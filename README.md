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

# Server Metrics 2026-03-23 01:16:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 101379.4 (28h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3523235
telemt_connections_bad_total 311767
telemt_connections_current 961
telemt_connections_me_current 961
telemt_handshake_timeouts_total 109559
telemt_upstream_connect_attempt_total 37659
telemt_upstream_connect_success_total 37658
telemt_upstream_connect_attempts_per_request{bucket="1"} 37658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1396
telemt_me_reconnect_success_total 602
telemt_me_reader_eof_total 618
telemt_me_idle_close_by_peer_total 618
telemt_me_route_drop_no_conn_total 2985416
telemt_me_route_drop_channel_closed_total 1233
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2908813
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 712
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 792
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12498
telemt_desync_full_logged_total 3922
telemt_desync_suppressed_total 8576
telemt_desync_frames_bucket_total{bucket="1_2"} 3369
telemt_desync_frames_bucket_total{bucket="3_10"} 4551
telemt_desync_frames_bucket_total{bucket="gt_10"} 4578
telemt_pool_swap_total 112
telemt_pool_force_close_total 3457
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 34490
telemt_me_writer_removed_unexpected_total 596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2478
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32256
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31033
telemt_me_writer_teardown_success_total{mode="normal"} 34734
telemt_me_writer_teardown_noop_total 34501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.027455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2897892
telemt_user_connections_current{user="hello"} 961
telemt_user_octets_from_client{user="hello"} 41422017508 (38.58 GB)
telemt_user_octets_to_client{user="hello"} 794137359432 (739.60 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 114745.9 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4002177
telemt_connections_bad_total 368727
telemt_connections_current 188
telemt_connections_me_current 188
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100763
telemt_upstream_connect_attempt_total 71685
telemt_upstream_connect_success_total 70835
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 71592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10100
telemt_me_reconnect_success_total 3615
telemt_me_reader_eof_total 3613
telemt_me_idle_close_by_peer_total 3613
telemt_me_route_drop_no_conn_total 3641064
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3179624
telemt_me_endpoint_quarantine_total 912
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 897
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
telemt_me_writers_active_current 43
telemt_desync_total 12959
telemt_desync_full_logged_total 7266
telemt_desync_suppressed_total 5693
telemt_desync_frames_bucket_total{bucket="1_2"} 2940
telemt_desync_frames_bucket_total{bucket="3_10"} 5080
telemt_desync_frames_bucket_total{bucket="gt_10"} 4939
telemt_pool_swap_total 107
telemt_pool_force_close_total 3071
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 47244
telemt_me_writer_removed_unexpected_total 3543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6211
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44609
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2613
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44173
telemt_me_writer_teardown_success_total{mode="normal"} 50820
telemt_me_writer_teardown_noop_total 47245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98065
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.617426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98065
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 3229
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 3192925
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 43074392779 (40.12 GB)
telemt_user_octets_to_client{user="hello"} 791675764540 (737.31 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 189605.9 (52h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16335810
telemt_connections_bad_total 1646899
telemt_connections_current 917
telemt_connections_me_current 917
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397470
telemt_upstream_connect_attempt_total 84966
telemt_upstream_connect_success_total 84861
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 84878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2998
telemt_me_reconnect_success_total 1574
telemt_me_reader_eof_total 1522
telemt_me_idle_close_by_peer_total 1520
telemt_me_route_drop_no_conn_total 14046208
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12976846
telemt_me_endpoint_quarantine_total 1257
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1427
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 53842
telemt_desync_full_logged_total 17097
telemt_desync_suppressed_total 36745
telemt_desync_frames_bucket_total{bucket="1_2"} 12002
telemt_desync_frames_bucket_total{bucket="3_10"} 21010
telemt_desync_frames_bucket_total{bucket="gt_10"} 20830
telemt_pool_swap_total 205
telemt_pool_force_close_total 6722
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1063
telemt_me_draining_writers_reap_progress_total 64397
telemt_me_writer_removed_unexpected_total 1465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5491
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57675
telemt_me_writer_teardown_success_total{mode="normal"} 65138
telemt_me_writer_teardown_noop_total 64450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129588
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.777845
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129588
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1063
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1362
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12976875
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 191138984553 (178.01 GB)
telemt_user_octets_to_client{user="hello"} 3489568996311 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 189607.0 (52h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11882120
telemt_connections_bad_total 1235751
telemt_connections_current 542
telemt_connections_me_current 542
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344595
telemt_upstream_connect_attempt_total 99343
telemt_upstream_connect_success_total 98017
telemt_upstream_connect_fail_total 873
telemt_upstream_connect_attempts_per_request{bucket="1"} 98890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 873
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4432
telemt_me_reconnect_success_total 1882
telemt_me_reader_eof_total 1749
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 4556194
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8820700
telemt_me_endpoint_quarantine_total 1266
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1446
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 38809
telemt_desync_full_logged_total 13068
telemt_desync_suppressed_total 25741
telemt_desync_frames_bucket_total{bucket="1_2"} 9612
telemt_desync_frames_bucket_total{bucket="3_10"} 14903
telemt_desync_frames_bucket_total{bucket="gt_10"} 14294
telemt_pool_swap_total 202
telemt_pool_force_close_total 6079
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 62612
telemt_me_writer_removed_unexpected_total 1779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56533
telemt_me_writer_teardown_success_total{mode="normal"} 64247
telemt_me_writer_teardown_noop_total 62637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126884
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.430047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126884
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8758459
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 217817616008 (202.86 GB)
telemt_user_octets_to_client{user="hello"} 3963978684675 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 189571.2 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11060619
telemt_connections_bad_total 975555
telemt_connections_current 507
telemt_connections_me_current 507
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345586
telemt_upstream_connect_attempt_total 83590
telemt_upstream_connect_success_total 82031
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 82236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5745
telemt_me_reconnect_success_total 2369
telemt_me_reader_eof_total 2114
telemt_me_idle_close_by_peer_total 2113
telemt_me_route_drop_no_conn_total 5337843
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8360026
telemt_me_endpoint_quarantine_total 1332
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1404
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
telemt_me_writers_active_current 43
telemt_desync_total 38183
telemt_desync_full_logged_total 12641
telemt_desync_suppressed_total 25542
telemt_desync_frames_bucket_total{bucket="1_2"} 9643
telemt_desync_frames_bucket_total{bucket="3_10"} 14607
telemt_desync_frames_bucket_total{bucket="gt_10"} 13933
telemt_pool_swap_total 198
telemt_pool_force_close_total 5979
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 740
telemt_me_draining_writers_reap_progress_total 62965
telemt_me_writer_removed_unexpected_total 2264
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6328
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56986
telemt_me_writer_teardown_success_total{mode="normal"} 65161
telemt_me_writer_teardown_noop_total 63036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.787576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 740
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8351985
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 192774438403 (179.54 GB)
telemt_user_octets_to_client{user="hello"} 3471497552961 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 59851.0 (16h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11249319
telemt_connections_bad_total 669169
telemt_connections_current 908
telemt_connections_me_current 908
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 273001
telemt_upstream_connect_attempt_total 58117
telemt_upstream_connect_success_total 55059
telemt_upstream_connect_fail_total 2028
telemt_upstream_connect_attempts_per_request{bucket="1"} 57087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2028
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7762
telemt_me_reconnect_success_total 1251
telemt_me_reader_eof_total 782
telemt_me_idle_close_by_peer_total 781
telemt_me_route_drop_no_conn_total 25291005
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9335419
telemt_me_endpoint_quarantine_total 451
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16343
telemt_desync_full_logged_total 4459
telemt_desync_suppressed_total 11884
telemt_desync_frames_bucket_total{bucket="1_2"} 3094
telemt_desync_frames_bucket_total{bucket="3_10"} 6657
telemt_desync_frames_bucket_total{bucket="gt_10"} 6592
telemt_pool_swap_total 62
telemt_pool_force_close_total 2020
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 18754
telemt_me_writer_removed_unexpected_total 1139
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2549
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1713
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16734
telemt_me_writer_teardown_success_total{mode="normal"} 19836
telemt_me_writer_teardown_noop_total 18773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38609
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.886856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38609
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 339
telemt_me_writer_restored_same_endpoint_total 802
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 9361296
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 87293567874 (81.30 GB)
telemt_user_octets_to_client{user="hello"} 609790347398 (567.91 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 189577.4 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10996350
telemt_connections_bad_total 947066
telemt_connections_current 714
telemt_connections_me_current 714
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242269
telemt_upstream_connect_attempt_total 112519
telemt_upstream_connect_success_total 111359
telemt_upstream_connect_fail_total 987
telemt_upstream_connect_attempts_per_request{bucket="1"} 112346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 987
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72949
telemt_me_reconnect_success_total 3088
telemt_me_reader_eof_total 2776
telemt_me_idle_close_by_peer_total 2774
telemt_me_route_drop_no_conn_total 5263304
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8678892
telemt_me_endpoint_quarantine_total 1278
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1433
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
telemt_me_writers_active_current 45
telemt_desync_total 46254
telemt_desync_full_logged_total 15842
telemt_desync_suppressed_total 30412
telemt_desync_frames_bucket_total{bucket="1_2"} 9402
telemt_desync_frames_bucket_total{bucket="3_10"} 17705
telemt_desync_frames_bucket_total{bucket="gt_10"} 19147
telemt_pool_swap_total 194
telemt_pool_force_close_total 5692
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67120
telemt_me_writer_removed_unexpected_total 2804
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63102
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61428
telemt_me_writer_teardown_success_total{mode="normal"} 69960
telemt_me_writer_teardown_noop_total 67121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.268416
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 4300
telemt_me_writer_restored_same_endpoint_total 2604
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8681870
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 194630086249 (181.26 GB)
telemt_user_octets_to_client{user="hello"} 3319114583644 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 126413.7 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11703410
telemt_connections_bad_total 482431
telemt_connections_current 512
telemt_connections_me_current 512
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762031
telemt_upstream_connect_attempt_total 60847
telemt_upstream_connect_success_total 60403
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 60836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_reconnect_attempts_total 48984
telemt_me_reconnect_success_total 1820
telemt_me_reader_eof_total 1492
telemt_me_idle_close_by_peer_total 1491
telemt_me_route_drop_no_conn_total 4093629
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5623426
telemt_me_endpoint_quarantine_total 855
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 968
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31623
telemt_desync_full_logged_total 10787
telemt_desync_suppressed_total 20836
telemt_desync_frames_bucket_total{bucket="1_2"} 6295
telemt_desync_frames_bucket_total{bucket="3_10"} 12473
telemt_desync_frames_bucket_total{bucket="gt_10"} 12855
telemt_pool_swap_total 134
telemt_pool_force_close_total 3907
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 46406
telemt_me_writer_removed_unexpected_total 1543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3808
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44184
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3466
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42499
telemt_me_writer_teardown_success_total{mode="normal"} 47992
telemt_me_writer_teardown_noop_total 46413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94405
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.692409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94405
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 2740
telemt_me_writer_restored_same_endpoint_total 1611
telemt_me_writer_restored_fallback_total 28
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5615581
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 119121401884 (110.94 GB)
telemt_user_octets_to_client{user="hello"} 2180934451882 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 107384.5 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1525551
telemt_connections_bad_total 36731
telemt_connections_current 395
telemt_connections_me_current 395
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30923
telemt_upstream_connect_attempt_total 50654
telemt_upstream_connect_success_total 50496
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 50626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2251
telemt_me_reconnect_success_total 915
telemt_me_reader_eof_total 902
telemt_me_idle_close_by_peer_total 902
telemt_me_route_drop_no_conn_total 518115
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355843
telemt_me_endpoint_quarantine_total 893
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 888
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 9033
telemt_desync_full_logged_total 2630
telemt_desync_suppressed_total 6403
telemt_desync_frames_bucket_total{bucket="1_2"} 2547
telemt_desync_frames_bucket_total{bucket="3_10"} 3444
telemt_desync_frames_bucket_total{bucket="gt_10"} 3042
telemt_pool_swap_total 116
telemt_pool_force_close_total 2961
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 42860
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3276
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2873
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39899
telemt_me_writer_teardown_success_total{mode="normal"} 43769
telemt_me_writer_teardown_noop_total 42864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.312650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1351657
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 26012962097 (24.23 GB)
telemt_user_octets_to_client{user="hello"} 575849532115 (536.30 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 189582.2 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13327192
telemt_connections_bad_total 1600896
telemt_connections_current 611
telemt_connections_me_current 611
telemt_handshake_timeouts_total 388962
telemt_upstream_connect_attempt_total 74643
telemt_upstream_connect_success_total 74292
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 74507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2975
telemt_me_reconnect_success_total 1491
telemt_me_reader_eof_total 1475
telemt_me_idle_close_by_peer_total 1475
telemt_me_route_drop_no_conn_total 4483534
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10050876
telemt_me_endpoint_quarantine_total 1356
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1434
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
telemt_me_writers_active_current 46
telemt_desync_total 42081
telemt_desync_full_logged_total 13745
telemt_desync_suppressed_total 28336
telemt_desync_frames_bucket_total{bucket="1_2"} 10177
telemt_desync_frames_bucket_total{bucket="3_10"} 15468
telemt_desync_frames_bucket_total{bucket="gt_10"} 16436
telemt_pool_swap_total 210
telemt_pool_force_close_total 5596
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 67477
telemt_me_writer_removed_unexpected_total 1413
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5320
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63622
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5422
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61881
telemt_me_writer_teardown_success_total{mode="normal"} 68942
telemt_me_writer_teardown_noop_total 67479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.789146
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1308
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10017583
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 194813505824 (181.43 GB)
telemt_user_octets_to_client{user="hello"} 4440318866856 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 189578.7 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11645096
telemt_connections_bad_total 1361411
telemt_connections_current 531
telemt_connections_me_current 531
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311626
telemt_upstream_connect_attempt_total 102146
telemt_upstream_connect_success_total 101258
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 101938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10477
telemt_me_reconnect_success_total 2585
telemt_me_reader_eof_total 2398
telemt_me_idle_close_by_peer_total 2397
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5650730
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8961275
telemt_me_endpoint_quarantine_total 1531
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1436
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41818
telemt_desync_full_logged_total 13460
telemt_desync_suppressed_total 28358
telemt_desync_frames_bucket_total{bucket="1_2"} 10804
telemt_desync_frames_bucket_total{bucket="3_10"} 15380
telemt_desync_frames_bucket_total{bucket="gt_10"} 15634
telemt_pool_swap_total 200
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67522
telemt_me_writer_removed_unexpected_total 2439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6674
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62146
telemt_me_writer_teardown_success_total{mode="normal"} 70046
telemt_me_writer_teardown_noop_total 67527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137573
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.468740
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137573
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2081
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8965862
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 157369493304 (146.56 GB)
telemt_user_octets_to_client{user="hello"} 3490325348966 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 63
```